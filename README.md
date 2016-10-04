# react-native-auto-scroll

> ScrollView that scrolls down responsively.

<img width="375" src="https://raw.githubusercontent.com/fritx/react-native-auto-scroll/dev/demo.gif">


```jsx
import AutoScroll from 'react-native-auto-scroll'

<View style={styles.msgsView}>
  <AutoScroll
    contentContainerStyle={styles.scrollContainer}>
    {this.state.messages.map(msg => {
      return <Message key={msg.id} message={msg} />
    })}
  </AutoScroll>
</View>
<TextInput style={styles.textInput} />
```

For more available props: [Docs of ScrollView](https://facebook.github.io/react-native/docs/scrollview.html)
