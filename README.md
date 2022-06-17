# Hey! <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px" height="25px"></a>

### <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50"> A little about me...  

```dart
class SoftwareDeveloper{
  
  SoftwareDeveloper(){
    final String fullName = "Aqib Hamid";
    final role = "Software Developer";
    final List languagesISpeak = ["en_US","bn_BD"];
    
    print("Hi, my name is $fullName. A $role from Bangladesh who codes for passion and design for fun.");
    _currentFocus();
    _futureGoal();
    
  }
  
  _currentFocus() => print("Currently writing clear Mobile Applications that are meaningful and solve a specific problem.");
  
  _futureGoal() => print("My future goal is to secure a position as a Lead Software Engineer and contribute to open source projects.");
  
  Map<String,dynamic> get  getTechnologies => {'mobile_app':{'flutter':<String>["android","ios"],'native':"android"},
                                               'programming_lang':<String>["C++","Java","Dart","JavaScript"],
                                               'web':<String>["HTML","CSS","NextJs"],
                                              'misc':<String>["Firebase","Selenium"]};
  
  sayHi() => print("Thanks for dropping by, hope you find some of my work interesting.");
  
}

main() {
  final me = SoftwareDeveloper();
  print("\nTechnologies I am familiar with -> ${me.getTechnologies}\n");
  me.sayHi();
}
```

## 💬 Contact
	
- IG: [@aquib.hamid](https://www.instagram.com/aquib.hamid/)
