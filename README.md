# FlycoRoundView2
An Android library aims to replace shape resource type and you need not to write a lot of shape xmls.Let you draw the View with round corners easily.
## Thanks [FlycoRoundView](https://github.com/H07000223/FlycoRoundView)
## FlycoRoundView2 New features：
- support ConstrainttLayout
## Support View：
- TextView
- ConstraintLayout
- FrameLayout
- LinearLayout
- RelativeLayout

## Demo
![](https://github.com/H07000223/FlycoRoundView/blob/master/preview.gif)

# Download
### Step 1. Add the JitPack repository in your root build.gradle at the end of repositories:
```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
### Step 2. Add the dependency
```
dependencies {
	        implementation 'com.github.BryceLee:FlycoRoundView:Tag'
	}
```

### Attributes

|name|format|description|
|:---:|:---:|:---:|
| rv_backgroundColor | color | background color
| rv_backgroundPressColor | color | background press color
| rv_cornerRadius | dimension | background rectangle corner radius,unit dp
| rv_strokeWidth | dimension | background rectangle stroke width,unit dp
| rv_strokeColor | color |background rectangle stroke color
| rv_strokePressColor | color |background rectangle stroke press color
| rv_textPressColor | color |text press color
| rv_isRadiusHalfHeight | boolean | corner radius is half of height
| rv_isWidthHeightEqual | boolean | width and height is the same size which is the max value of them
| rv_cornerRadius_TL | dimension | corner radius top left,unit dp
| rv_cornerRadius_TR | dimension | corner radius top right,unit dp
| rv_cornerRadius_BL | dimension | corner radius bottom left,unit dp
| rv_cornerRadius_BR | dimension | corner radius bottom right,unit dp
| rv_isRippleEnable | boolean | is ripple effect enable for Api21+

