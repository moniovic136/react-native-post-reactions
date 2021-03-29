**This React Native component provides a way to react just like facebook. **


We have 5 reactions. 

1. Like
2. Love
3. Haha
4. Yay
5. Wow
6. Sad
7. Angry

Installing is pretty simple:


**npm install react-native-post-reactions**


**Example:**


```
import PostReact from 'react-native-post-reactions'

const App = () => {
    const emojiPressed = (emoji) => {
        console.log(`User reacted with ${emoji}`)
    }
   return (
         <PostReactView callBack={emojiPressed} />
   )
}
```
