# sass-mixin-padding-margin


Mixin to generate padding or margin

@param {string} $padding-margin - Only padding or margin words are accepted 
@param {number} $limiter - maximum padding/margin value
@param {number} $step - step for incrementation

Usage:
@include padding-margin(padding, 40, 5);
@include padding-margin(margin, 40, 5);
 
