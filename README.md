# sass-media-query-mixins

![Screenshot from 2021-10-04 02-08-13](https://user-images.githubusercontent.com/23323551/135941002-3602aa71-435f-416d-91a9-66561e172070.png)

## features in this files

1. mixins for (min-width) media query.
2. mixins for (max-width) media query.
3. mixins for specific screens (min-width && max-width) media query.
4. you can also change the breakpoints of your devices



## how to use it 
1. download the file.
2. import it in your main scss file.
3.  in your scss **main file** write the below code:
```
@import url"media.mixin"
```
4. use the mixins in the mixin file write the below code:
  ```
  @include mobile-sm {
    .elment__here{
      property: value;
    }
  }
  
  @include to-mobile-sm {
    .elment__here{
      property: value;
    }
  }
  
  
  @include from-mobile-sm {
    .elment__here{
      property: value;
    }
  }
  ```
## how to customize breakpoints:

- in the **_media.mixin.scss** only change the variables
- you can also make your mixins adding your breakpoints and go on.
