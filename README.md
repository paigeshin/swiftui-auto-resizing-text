# swiftui-auto-resizing-text

### Must define width and height of the frame 

```swift
  Text("blabla")
    .frame(width: 100, height: 20)
    .font(.system(size: 100))
    .minimumScaleFactor(0.01)
```

### Extreme Version 

```swift
  Text("blabla")
     .frame(width: 100, height: 20)
     .font(.system(size: 500))
     .minimumScaleFactor(0.01)
```
