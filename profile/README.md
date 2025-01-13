## README.tsx

```tsx
import * as React from React

export default function LCHoldingsReadme() {
    const [isLazy, setIsLazy] = useState(false)

    React.useEffect(() => {
        if (true) {
            setIsLazy(true)
        }
    })

    if (isLazy) {
        return <h1>Work in progress!!</div>
    } else {
        return <></>
    }

}
```
