#scss

For SASS and COMPASS awesomeness

##Style Guide

###BEM 

BEM can be useful: http://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/

###SCSS your BEM

Here's a good example: 

```
.block {
    /* CSS declarations for `.block` */

    &__element {
        /* CSS declarations for `.block__element` */
    }

    &--modifier {
        /* CSS declarations for `.block--modifier` */

        &__element {
            /* CSS declarations for `.block--modifier__element` */
        }
    }
}
```

#CSS Rules

- make properties alphabetical within a selector
- use specific overrides rather than shorthand overrides, avoid repeating code
- do not use elements as part of the selector
- use rem for fonts
- use px for padding/margin


