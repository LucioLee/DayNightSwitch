# DayNightSwitch
So I came across this awesome, kinda skeuomorphic-ish custom switch design on Dribbble and thought it was cute, so here you go:
[![gif](https://d13yacurqjgara.cloudfront.net/users/470545/screenshots/1909289/switch_02.gif)](https://dribbble.com/shots/1909289-Day-Night-Toggle-Button-GIF)

## Installation
### CocoaPods
1. Add `pod 'DayNightSwitch` to your `Podfile`
2. Run `pod install`

### Manual
1. Clone or download the repo, drop the `DayNightSwitch.swift` file in your project and 
2. Either drop a `UIView` into your storyboard and set its class to `DayNightButton` or create an instance of the switch like so:

## Usage
```
    let dayNightSwitch = DayNightSwitch(center: self.view.center)
    dayNightSwitch.changeAction = { on in
        print("The switch is now " + (on ? "on" : "off"))
    }
    self.view.addSubview(dayNightSwitch)
```

## License
Original credit for the design goes to [Ramakrishna](https://dribbble.com/shots/1907553-Day-Night-Toggle-Button) and for the animations to [Tsuriel](https://dribbble.com/shots/1909289-Day-Night-Toggle-Button-GIF)
[MIT](LICENSE).
