## Hi, I'm Eugene 👋

*  about 2 year of experience in iOS Application development of commercial projects.
*  passionate about new technologies
*  like to study foreign languages
*  live in Ukraine
 ```
 func calcAge(birthday: String) -> Int {
    let dateFormater = DateFormatter()
    dateFormater.dateFormat = "MM/dd/yyyy"
    let birthdayDate = dateFormater.date(from: birthday)
    let calendar: NSCalendar = NSCalendar(calendarIdentifier: .gregorian)
    let now = Date()
    let calcAge = calendar.components(.year, from: birthdayDate, to: now, options: [])
    guard let age = calcAge.year else { return }
    return age
   }
calcAge(05/01/1997)
```

👔 [linkedin][linkedin]

[linkedin]: https://www.linkedin.com/in/eugene-bychkailo-8479931a8/


