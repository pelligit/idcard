# ID card
Get an Chinese ID card number and Check an Chinese ID card number.

### get an ID card number,the ID card number only has truly format,It's not the same as police's;
```javascript
// get an Chinese ID card number.
var a_card_number = _$id.getCardNumber();
//check an ID card number is right format.
_$id.checkCardNumber(a_card_number);//true

_$id.checkCardNumber(13278473554);//false

_$id.checkCardNumber(234567891037287);//false

_$id.checkCardNumber("320104197710117121");//true
```
### tips
The params for check method(_id.checkCardNumber) must be a String,if the params is Number type,there's a bug for the number over the range of number in javascript;
