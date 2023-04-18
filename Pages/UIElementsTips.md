## UIElements Tips
- To instantiate a visual element at runtime you can use 
 ```csharp
var _newElement = Resources.Load<VisualTreeAsset>(RESOURCES_ELEMENTNAME_WITHOUT_EXTENSION);
VisualElement _thisIsTheVisualElement = _newElement.CloneTree();
Panel.Add(_thisIsTheVisualElement); 
```
 
- Bind with
```csharp
 _thisVisualElement.Init(Enum.Type);  
 _thisVisualElement.RegisterValueChangedCallback(FunctionToBeCalled);
```
