---
-api-id: M:Windows.UI.Input.Preview.Injection.InputInjector.UninitializePenInjection
-api-type: winrt method
---

<!-- Method syntax
public void UninitializePenInjection()
-->

# Windows.UI.Input.Preview.Injection.InputInjector.UninitializePenInjection

## -description

Shuts down the virtual pen device created with [InitializePenInjection](inputinjector_initializepeninjection_260722924.md).

## -remarks

> [!Important]
> The APIs in this namespace require the inputInjectionBrokered [restricted capability](https://docs.microsoft.com/windows/uwp/packaging/app-capability-declarations#special-and-restricted-capabilities).

Using input injection requires the following be added to the Package.appxmanifest:

- To `<Package>`
    - `xmlns:rescap="http://schemas.microsoft.com/appx/manifest/foundation/windows10/restrictedcapabilities"`
    - `IgnorableNamespaces="rescap"`
- To `<Capabilities>`
    - `<rescap:Capability Name="inputInjectionBrokered" />`

## -examples

Here are some downloadable samples demonstrating basic input and input injection:

- [Input injection sample (mouse to touch)](https://github.com/MicrosoftDocs/windows-topic-specific-samples/archive/uwp-input-injection-mouse-to-touch.zip)
- [Touch injection sample](https://go.microsoft.com/fwlink/p/?LinkID=267906)
- [Input: XAML user input events sample](https://go.microsoft.com/fwlink/p/?linkid=226855)

## -see-also

[InitializePenInjection](inputinjector_initializepeninjection_260722924.md), [Simulate user input through input injection](https://docs.microsoft.com/windows/uwp/design/input/input-injection)
