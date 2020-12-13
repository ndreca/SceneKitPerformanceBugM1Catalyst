
# SceneKit Performance Bug - Catalyst / M1 Apple Silicon

## Sample content:
- Default Game Template for iOS, configured with macOS deployment
- Modified Main.storyboard to add 3 times the GameViewController

## Steps to reproduce:

- build and run the app on M1 chip with target Mac (Rosetta) -> maximum display frame rate obtained in all 3 views
<img  src="3SCNViews_M1_Rosetta_MaxDisplayFrameRate.png"/>
- build the app with target Mac(native) - > frame rate drops on all 3 views to 1/3
<img  src="3SCNViews_M1_Native_FrameRateDrops.png"/>
