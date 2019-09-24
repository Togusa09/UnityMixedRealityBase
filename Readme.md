
# Base Mixed Reality Toolkit Project

Created following the [Mixed Reality Getting Started Guide](https://microsoft.github.io/MixedRealityToolkit-Unity/Documentation/GettingStartedWithTheMRTK.html)

Imported packages:

- Microsoft.MixedReality.Toolkit.Unity.Examples.2.0.0.unitypackage
- Microsoft.MixedReality.Toolkit.Unity.Extensions.2.0.0.unitypackage
- Microsoft.MixedReality.Toolkit.Unity.Foundation.2.0.0.unitypackage
- Microsoft.MixedReality.Toolkit.Unity.Tools.2.0.0.unitypackage

## Getting Started

1. Open the project in Unity
2. Load the scene appropriate for your target (HoloLens 1, 2 or WMR headset)
3. Hack away!

## Building

I had big issues getting Unity to install via the device portal, this was the best I could do

1. Go to "Mixed Reality Toolkit" => "Utilities" => "Build Window"
2. In the "Unity Build Options" tab, press "Build Unity Project"
3. In the "Appx Build Options" tab, press "Build Appx"
4. On the HoloLens, navigate to `http://<ipaddress-of-hololens>`
5. Go to "View"=>"Apps" and install the app from there.

There might be a better way, good luck :)

## Scene concepts

We have 3 scenes, and a shared prefab called "gameplay"

Any changes to the gameplay prefab should be saved back to the prefab, which will allow it to work in all the scenes.

Nested prefabs make this approach work :) - there's probably better ways, but this is what we're doing for this.

## Documentation

See https://microsoft.github.io/MixedRealityToolkit-Unity/Documentation/GettingStartedWithTheMRTK.html for MRTK documenation
