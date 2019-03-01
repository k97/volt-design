--- 
name: Button 
category: Components 
---  

Buttons can be used with `<a>`, `<button>` elements.  

#### Types
- `primary` -  Provides extra visual weight and identifies the primary action in a set of buttons 
- `secondary` -  Identifies the secondary action in a set of buttons 
- `tertiary` -  Identifies the tertiary or low level action in a set of buttons 
- `success` -  Indicates a successful or positive action
- `danger` -  Indicates a warning or negative action

#### Additional Config
- `small` - Small buttons
- `large` - Large buttons


#### Reference:
```type.js
	@HostBinding("class.bx--btn--primary") primary = true;
	@HostBinding("class.bx--btn--secondary") secondary = false;
	@HostBinding("class.bx--btn--tertiary") tertiary = false;
	@HostBinding("class.bx--btn--danger") danger = false;
	@HostBinding("class.bx--skeleton") @Input() linkBtn = false;
	@HostBinding("class.bx--btn--sm") smallSize = false;
```

