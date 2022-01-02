### Hi there 👋

```js
import { useState, useEffect } from 'react'

export default function App() {
  const [knowledge, setKnowledge] = useState([])
  const [name, setName] = useState('Sharky')
  
  useEffect(() => {
    setKnowledge(['Javascript', 'PHP', 'HTML', 'CSS', 'React Native'])
  }, [])
  
  return (
    <div>
      My knowledge: 
      <ul>
      {
        knowledge.map((data) => {
          return (
            <li>data</li>
          )
        })
      }
      </ul>
      <br />
      My name: {name}
    </div>
  )
}
```

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=sharkydeveloping&show_icons=true&theme=radical)
