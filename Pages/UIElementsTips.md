## UIElements Tips
- To instantiate a visual element at runtime you can use 
`var _newElement = Resources.Load<VisualTreeAsset>(RESOURCES_ELEMENTNAME_WITHOUT_EXTENSION);
 VisualElement _thisIsTheVisualElement = _newElement.CloneTree();
 Panel.Add(_thisIsTheVisualElement);
 `
- Bind with
` dropdown.Init(Enum.Type);  
  dropdown.RegisterValueChangedCallback(FunctionToBeCalled);`