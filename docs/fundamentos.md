# Fundamentos de SwiftUI

SwiftUI es el framework declarativo de Apple para crear interfaces en todas sus plataformas.

## Ejemplo básico

```swift
import SwiftUI

struct ContentView: View {
    var body: some View {
        Text("Hola, SwiftUI!")
            .font(.title)
            .padding()
    }
}
```