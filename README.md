# atr-inline-rtl-ltr-releases
Atr Inline Rtl Ltr releases

First release

Wrap words (or sentences) in paragraph block with span element and change their direction from rtl to ltr and vice versa.

We use here dir="rtl" or dir="ltr" (See also https://www.w3.org/International/articles/inline-bidi-markup/).

Note that the wrapping element is <span dir="rtl" || dir="ltr" class="atr-inline-direction-rtl" || class="atr-inline-direction-ltr"> so you can control it through your site CSS as well. I.E. .atr-inline-direction-rtl{direction: rtl;display:inline-block}
  
This is a toggled element, which means, if you click again it will remove the added span.
