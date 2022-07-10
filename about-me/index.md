# Create an About Me app

Steps:

1. Use a `TabView`.
2. Create a summary section.

## Use a `TabView`

First, start with this template:

```swift
import SwiftUI

struct ContentView: View {
    var body: some View {
        TabView {
            Text("Hello, world!")
                .tabItem {
                    Label("Summary", systemImage: "person")
                }
        }
    }
}
```

## Create a summary section

Next, we'll be creating a summary section. Start with this in the `SummaryView.swift` file:

```swift
import SwiftUI

struct SummaryView: View {
    var body: some View {
        Text("Bruno")
            .font(.largeTitle)
    }
}

struct SummaryView_Previews: PreviewProvider {
    static var previews: some View {
        SummaryView()
    }
}
```
