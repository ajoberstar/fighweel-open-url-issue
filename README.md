# figwheel-open-url-issue

Reproduce with:

1. `clj`
1. `(require 'figwheel.main)`
1. `(figwheel.main/start {:open-url false} {:id "dev" :options {:main 'example.core}})`

You'll see a HeadlessExample if you're in a headless JVM.

Maybe you'll need to force it with `-Djava.awt.headless=true` if you're not in a headless environment.
