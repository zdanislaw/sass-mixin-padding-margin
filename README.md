# sass-mixin-padding-margin


Mixin to generate padding or margin

@param {string} $padding-margin - Only padding or margin words are accepted<br/> 
@param {number} $limiter - maximum padding/margin value<br/>
@param {number} $step - step for incrementation

Usage:
@include padding-margin(padding, 40, 5);<br/>
@include padding-margin(margin, 40, 5);
 
