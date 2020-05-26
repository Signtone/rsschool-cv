# **ALEH BAN**

- Email: actionx@list.ru
- Phone: +375 (44) 712-82-22
- Telegram: @Signtone
- Linkedin: [https://www.linkedin.com/in/signtone/](https://www.linkedin.com/in/signtone/)

# **Summary**

> Beginning front-end developer passionate about IT. I love to learn new things and absorb new information. The main goal at the moment is to become a good front-end specialist with the subsequent transition to full-stack development. I am also fond of iOS development and Swift language.

# **Main Skills**

- Html
- CSS
- Java Script
- Swift
- xCode
- Git
- MsSql
- VS code

# **Code examples**

```javascript
function convertMoney(amount, outputId) {
  var inputIndex = getRate(requestCurrency);
  var outputIndex = getRate(currency);

  if (requestCurrency === "BYN") {
    if (currency === "BYN") {
      var value = (1 * amount).toFixed(2);
      setOutputValue(value, outputId);
    } else {
      getValue(outputIndex).then(function (requestRes) {
        var value = (amount / requestRes).toFixed(2);
        setOutputValue(value, outputId);
      });
    }
  } else if (currency === "BYN") {
    getValue(inputIndex).then(function (requestRes) {
      var value = (amount * requestRes).toFixed(2);
      setOutputValue(value, outputId);
    });
  } else {
    getValue(inputIndex).then(function (res) {
      getValue(outputIndex).then(function (requestRes) {
        var value = ((res / requestRes) * amount).toFixed(2);
        setOutputValue(value, outputId);
      });
    });
  }
}
```

# **Experience**

> As a training project for the defense of the discipline “Development and design of web applications”, developed the web application “currency converter” using the open Api of the “National Bank of the Republic of Belarus”.

[Github link](https://github.com/Signtone/JavaScript/tree/master/JavaScript/Study/CurrencyConverter%20on%20JS)

> As a graduation project, developed the “TourMan” application for mobile phones on the iOS platform in Swift language.

[Github link](https://github.com/Signtone/Swift/tree/master/Study/TourMan%201.0.0)

# **Education**

## Belarusian State University:

#### **_Bachelor's degree, Software design of information systems_**

## Certificate:

#### **_Software project management_**

#### **_Business analyses foundation_**

## Online Courses:

#### **_Html academy_**

# **English level**

A2+ Pre-Intermediate
