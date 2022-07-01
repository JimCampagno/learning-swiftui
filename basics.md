# Some Fundamentals

source: https://developer.apple.com/tutorials/swiftui/creating-and-combining-views

- An app that uses the SwiftUI app life cycle has a structure that conforms to the App protocol. The structure’s `body` property returns one or more `Scene`s, which in turn provide content for display. The `@main` attribute identifies the app’s entry point.
- You can combine and embed multiple views in stacks, which group views together horizontally, vertically, or back-to-front.
- A `Spacer` expands to make its containing view use all of the space of its parent view, instead of having its size defined only by its contents.
- The `Circle` type is a shape that you can use as a mask, or as a view by giving the circle a stroke or fill.
- When you import SwiftUI and certain other frameworks in the same file, you gain access to SwiftUI-specific functionality provided by that framework.
- You use the `@State` attribute to establish a source of truth for data in your app that you can modify from more than one view. SwiftUI manages the underlying storage and automatically updates views that depend on the value.
- By prefixing a state variable with $, you pass a binding, which is like a reference to the underlying value. When the user interacts with the map, the map updates the region value to match the part of the map that’s currently visible in the user interface.
- When you specify only the height parameter, the view automatically sizes to the width of its content. In this case, MapView expands to fill the available space.
- When you apply a modifier to a layout view like a stack, SwiftUI applies the modifier to all the elements contained in the group.