# Swift-Articles-Tutorials-Videos

### [5 Ways to Pass Data Between View Controllers](https://betterprogramming.pub/5-ways-to-pass-data-between-view-controllers-18acb467f5ec)

1. Segues
```swift
class FirstViewController{
  let destinationVC = segue.destination as! SecondViewController
  destinationVC.nickName = nickName
} 
class SecondViewController{
  //a variable to hold the data from the first ViewController
  var nickName: String = ""
}
```

[2. Delegate design pattern](https://github.com/Brian-McIntosh/Delegate-Design-Pattern)

3. Singleton design pattern
4. Closures
5. Notification Center

