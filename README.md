<div align="center">

# 🧩 GpuImageTools

**An extension for MIT App Inventor 2**

> GPU Image Tools - Advanced image filtering and processing using GPU acceleration, it is a high-performance image processing extension for MIT App Inventor 2. It leverages the power of GPU acceleration via the OpenGLES-based GPUImage library to provide real-time filtering, rotating, and editing capabilities with professional-grade results. Developed by TechHamara. Find More ExtensionTerms & ConditionsFind More On BuyMeCoffee Page

</div>

## 📝 Specifications
* **
📦 **Package:** io.th.gpuimagetools<br>
💾 **Size:** 152.15 KB<br>
⚙️ **Version:** 1.0<br>
📱 **Minimum API Level:** 14<br>
📅 **Updated On:** [date=2026-03-17 timezone="Asia/Calcutta"]<br>


## **GpuImageTools** has total 5 events.

### 1. FilterApplied
Triggered when a filter is successfully applied

| Parameter | Type |
| - | - |
| filterName | text |
| value | number |

### 2. ImageLoaded
Triggered when an image is successfully loaded

| Parameter | Type |
| - | - |
| imagePath | text |

### 3. ProcessingError
Triggered when an error occurs during processing

| Parameter | Type |
| - | - |
| errorMessage | text |

### 4. ImageSaved
Triggered when an image is successfully saved

| Parameter | Type |
| - | - |
| filePath | text |

### 5. FilterListRequested
Triggered when list of available filters is requested

| Parameter | Type |
| - | - |
| filterList | text |

## <kbd>Methods:</kbd>
**GpuImageTools** has total 41 methods.

### 1. Initialize
Initialize GPU Image inside an arrangement view.

| Parameter | Type |
| - | - |
| arrangement | component |

### 2. BulgeDistortionFilter
Apply BulgeDistortion filter to the image. ex: radius 0.0 to 1.0, scale -1.0 to 1.0

| Parameter | Type |
| - | - |
| radius | number |
| scale | number |

### 3. CGAColorspaceFilter
Apply CGAColorspace filter to the image.

### 4. ColorBalanceFilter
Apply ColorBalance filter. Shadows/Midtones/Highlights R,G,B range: -1.0 to 1.0

| Parameter | Type |
| - | - |
| shadowsR | number |
| shadowsG | number |
| shadowsB | number |
| midtonesR | number |
| midtonesG | number |
| midtonesB | number |
| highlightsR | number |
| highlightsG | number |
| highlightsB | number |
| preserveLuminosity | boolean |

### 5. ColorInvertFilter
Apply ColorInvert filter to the image.

### 6. CrosshatchFilter
Apply Crosshatch filter to the image. ex: crossHatchSpacing 0.0 to 0.02, lineWidth 0.0 to 0.01

| Parameter | Type |
| - | - |
| crossHatchSpacing | number |
| lineWidth | number |

### 7. DilationFilter
Apply Dilation filter to the image.

### 8. FalseColorFilter
Apply FalseColor filter to the image. ex: firstColor 0x00000000 to 0xFFFFFFFF, secondColor 0x00000000 to 0xFFFFFFFF

| Parameter | Type |
| - | - |
| firstColor | number |
| secondColor | number |

### 9. GlassSphereFilter
Apply GlassSphere filter to the image. ex: refractiveIndex 0.0 to 2.0, radius 0.0 to 1.0

| Parameter | Type |
| - | - |
| refractiveIndex | number |
| radius | number |

### 10. GrayscaleFilter
Apply Grayscale filter to the image.

### 11. HalftoneFilter
Apply Halftone filter to the image. ex: fractionalWidthOfAPixel 0.0 to 1.0, aspectRatio 0.0 to 1.0

| Parameter | Type |
| - | - |
| fractionalWidthOfAPixel | number |
| aspectRatio | number |

### 12. HazeFilter
Apply Haze filter to the image. ex: distance -2.0 to 2.0, slope -2.0 to 2.0

| Parameter | Type |
| - | - |
| distance | number |
| slope | number |

### 13. HighlightShadowFilter
Apply HighlightShadow filter to the image. ex: highlights -1.0 to 1.0, shadows -1.0 to 1.0

| Parameter | Type |
| - | - |
| highlights | number |
| shadows | number |

### 14. LaplacianFilter
Apply Laplacian filter to the image.

### 15. LuminanceFilter
Apply Luminance filter to the image.

### 16. MonochromeFilter
Apply Monochrome filter to the image. ex: intensity 0.0 to 1.0, color 0 to 16777215

| Parameter | Type |
| - | - |
| intensity | number |
| color | number |

### 17. NonMaximumSuppressionFilter
Apply NonMaximumSuppression filter to the image.

### 18. RGBDilationFilter
Apply RGBDilation filter to the image.

### 19. RGBFilter
Apply RGB filter to the image.

| Parameter | Type |
| - | - |
| red | number |
| green | number |
| blue | number |

### 20. SepiaToneFilter
Apply SepiaTone filter to the image.

### 21. SketchFilter
Apply Sketch filter to the image.

### 22. SmoothToonFilter
Apply SmoothToon filter to the image. ex: value = 0.02, value1 = 0.02, value2 = 1.0, value3 = 0.2, value4 = 10.0

| Parameter | Type |
| - | - |
| value | number |
| value1 | number |
| value2 | number |
| value3 | number |
| value4 | number |

### 23. SphereRefractionFilter
Apply SphereRefraction filter to the image. ex: refractiveIndex = 1.0, radius = 0.5

| Parameter | Type |
| - | - |
| refractiveIndex | number |
| radius | number |

### 24. SwirlFilter
Apply Swirl filter to the image. ex: radius = 0.5, angle = 1.0

| Parameter | Type |
| - | - |
| radius | number |
| angle | number |

### 25. ThresholdEdgeDetectionFilter
Apply ThresholdEdgeDetection filter to the image. ex: size = 1.0, threshold = 0.5

| Parameter | Type |
| - | - |
| size | number |
| threshold | number |

### 26. AlphaBlendFilter
Apply AlphaBlend filter. mix: 0.0 (only image1) to 1.0 (only image2). blendImagePath: path to second image.

| Parameter | Type |
| - | - |
| blendImagePath | text |
| mix | number |

### 27. ChromaKeyBlendFilter
Apply ChromaKeyBlend (green screen). thresholdSensitivity: 0.0-1.0, smoothing: 0.0-1.0, colorToReplace: App Inventor color.

| Parameter | Type |
| - | - |
| blendImagePath | text |
| thresholdSensitivity | number |
| smoothing | number |
| colorToReplace | number |

### 28. DissolveBlendFilter
Apply DissolveBlend filter. mix: 0.0 (only image1) to 1.0 (only image2). blendImagePath: path to second image.

| Parameter | Type |
| - | - |
| blendImagePath | text |
| mix | number |

### 29. TransparentColor
Make a specific color transparent in the current image. targetColor: App Inventor color. tolerance: 0 to 255 (how much color difference is allowed).

| Parameter | Type |
| - | - |
| targetColor | number |
| tolerance | number |

### 30. ReplaceColorWithImage
Replace a specific color area in the current image with another image. targetColor: App Inventor color. replacementImagePath: path to replacement image. tolerance: 0 to 255.

| Parameter | Type |
| - | - |
| targetColor | number |
| replacementImagePath | text |
| tolerance | number |

### 31. ToonFilter
Apply Toon filter to the image. ex: threshold = 0.2, quantizationLevels = 10.0

| Parameter | Type |
| - | - |
| threshold | number |
| quantizationLevels | number |

### 32. TransformFilter
Apply Transform filter. scaleX/scaleY: scale factors (1.0=normal). translateX/translateY: translation (-1.0 to 1.0). rotateAngle: rotation in degrees.

| Parameter | Type |
| - | - |
| scaleX | number |
| scaleY | number |
| translateX | number |
| translateY | number |
| rotateAngle | number |
| ignoreAspectRatio | boolean |
| anchorTopLeft | boolean |

### 33. VignetteFilter
Apply Vignette filter to the image. ex: vignetteColor = 0, vignetteStart = 0.0, vignetteEnd = 0.5, centerX = 0.5, centerY = 0.5

| Parameter | Type |
| - | - |
| vignetteColor | number |
| vignetteStart | number |
| vignetteEnd | number |
| centerX | number |
| centerY | number |

### 34. WeakPixelInclusionFilter
Apply WeakPixelInclusion filter to the image.

### 35. WhiteBalanceFilter
Apply WhiteBalance filter to the image. ex: temperature = 5000.0, tint = 0.0

| Parameter | Type |
| - | - |
| temperature | number |
| tint | number |

### 36. ResetFilter
Reset image to original state (remove all filters).

### 37. RequestRender
Request the GPU Image renderer to update.

### 38. DeleteImage
Delete the current image and free memory.

### 39. GetAvailableFilters
Get list of all available filter names.

* Returns: `text`

### 40. GetCurrentBitmap
Get the current bitmap being displayed.

* Returns: `any`

### 41. GetImageDimensions
Get the dimensions of the current image as 'width,height'.

* Returns: `text`

## <kbd>Setters:</kbd>
**GpuImageTools** has total 52 setter properties.

### 1. ImageFromAssets
Load image from assets folder (supports companion mode).

* Input type: `text`

### 2. ImageFromPath
Load image from file path.

* Input type: `text`

### 3. BoxBlurFilter
Apply BoxBlur filter to the image. ex: 0.0 to 10.0

* Input type: `number`

### 4. BrightnessFilter
Apply Brightness filter to the image. ex: -1.0 to 1.0

* Input type: `number`

### 5. ContrastFilter
Apply Contrast filter to the image. ex: 0.0 to 2.0

* Input type: `number`

### 6. EmbossFilter
Apply Emboss filter to the image.

* Input type: `number`

### 7. ExposureFilter
Apply Exposure filter to the image.

* Input type: `number`

### 8. GammaFilter
Apply Gamma filter to the image. ex: 0.0 to 3.0

* Input type: `number`

### 9. GaussianBlurFilter
Apply GaussianBlur filter to the image. ex: 0.0 to 10.0

* Input type: `number`

### 10. HueFilter
Apply Hue filter to the image. ex: 0.0 to 360.0

* Input type: `number`

### 11. KuwaharaFilter
Apply Kuwahara filter to the image. ex: 0 to 10

* Input type: `number`

### 12. LookupFilter
Apply Lookup filter to the image. ex: 0.0 to 1.0

* Input type: `number`

### 13. LuminanceThresholdFilter
Apply LuminanceThreshold filter to the image. ex: 0.0 to 1.0

* Input type: `number`

### 14. PixelationFilter
Apply Pixelation filter to the image. ex: 0.0 to 0.1

* Input type: `number`

### 15. PosterizeFilter
Apply Posterize filter to the image. ex: 0 to 10

* Input type: `number`

### 16. SaturationFilter
Apply Saturation filter to the image. ex: 0.0 to 2.0

* Input type: `number`

### 17. SharpenFilter
Apply Sharpen filter to the image. ex: -4.0 to 4.0

* Input type: `number`

### 18. SobelEdgeDetectionFilter
Apply SobelEdgeDetection filter to the image. ex: 1.0 to 10.0

* Input type: `number`

### 19. SobelThresholdFilter
Apply SobelThreshold filter to the image. ex: 0.0 to 1.0

* Input type: `number`

### 20. SolarizeFilter
Apply Solarize filter to the image. ex: 0.0 to 1.0

* Input type: `number`

### 21. AddBlendFilter
Apply AddBlend filter. Blends a second image using additive blending. blendImagePath: path to second image.

* Input type: `text`

### 22. ColorBlendFilter
Apply ColorBlend filter. blendImagePath: path to second image.

* Input type: `text`

### 23. ColorBurnBlendFilter
Apply ColorBurnBlend filter. blendImagePath: path to second image.

* Input type: `text`

### 24. ColorDodgeBlendFilter
Apply ColorDodgeBlend filter. blendImagePath: path to second image.

* Input type: `text`

### 25. DarkenBlendFilter
Apply DarkenBlend filter. blendImagePath: path to second image.

* Input type: `text`

### 26. DifferenceBlendFilter
Apply DifferenceBlend filter. blendImagePath: path to second image.

* Input type: `text`

### 27. DivideBlendFilter
Apply DivideBlend filter. blendImagePath: path to second image.

* Input type: `text`

### 28. ExclusionBlendFilter
Apply ExclusionBlend filter. blendImagePath: path to second image.

* Input type: `text`

### 29. HardLightBlendFilter
Apply HardLightBlend filter. blendImagePath: path to second image.

* Input type: `text`

### 30. HueBlendFilter
Apply HueBlend filter. blendImagePath: path to second image.

* Input type: `text`

### 31. LightenBlendFilter
Apply LightenBlend filter. blendImagePath: path to second image.

* Input type: `text`

### 32. LinearBurnBlendFilter
Apply LinearBurnBlend filter. blendImagePath: path to second image.

* Input type: `text`

### 33. LuminosityBlendFilter
Apply LuminosityBlend filter. blendImagePath: path to second image.

* Input type: `text`

### 34. MultiplyBlendFilter
Apply MultiplyBlend filter. blendImagePath: path to second image.

* Input type: `text`

### 35. NormalBlendFilter
Apply NormalBlend filter. blendImagePath: path to second image.

* Input type: `text`

### 36. OverlayBlendFilter
Apply OverlayBlend filter. blendImagePath: path to second image.

* Input type: `text`

### 37. SaturationBlendFilter
Apply SaturationBlend filter. blendImagePath: path to second image.

* Input type: `text`

### 38. ScreenBlendFilter
Apply ScreenBlend filter. blendImagePath: path to second image.

* Input type: `text`

### 39. SoftLightBlendFilter
Apply SoftLightBlend filter. blendImagePath: path to second image.

* Input type: `text`

### 40. SourceOverBlendFilter
Apply SourceOverBlend filter. blendImagePath: path to second image.

* Input type: `text`

### 41. SubtractBlendFilter
Apply SubtractBlend filter. blendImagePath: path to second image.

* Input type: `text`

### 42. VibranceFilter
Apply Vibrance filter to the image. ex: -1.0 to 1.0

* Input type: `number`

### 43. ZoomBlurFilter
Apply ZoomBlur filter to the image. ex: 0.0 to 1.0

* Input type: `number`

### 44. ClearFilter
Remove a specific filter by name.

* Input type: `text`

### 45. SaveImage
Save the current filtered image to external storage.

* Input type: `text`

### 46. Rotation
Rotate the image. Degrees: 0, 90, 180, or 270.

* Input type: `number`

### 47. GetGPUImageInstance
Get the GPUImage instance for advanced operations.

* Input type: `any`

### 48. GetGPUImageViewInstance
Get the GPUImageView instance for advanced operations.

* Input type: `any`

### 49. IsInitialized
Check if GPU Image is properly initialized.

* Input type: `boolean`

### 50. CurrentFilterName
Get the name of the currently applied filter.

* Input type: `text`

### 51. CurrentRotation
Get the current rotation of the image.

* Input type: `number`

### 52. IsProcessing
Check if image processing is currently in progress.

* Input type: `boolean`


---

<div align="center">
<br>
<p>
📄 <strong>Documentation generated with</strong> <a href="https://techhamara.github.io/BlockLens/" target="_blank">ai-unchive</a>
</p>
<p>
<sub>🛠️ Built for MIT App Inventor 2 & its distributions</sub>
</p>
</div>
