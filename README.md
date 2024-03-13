# DateTime Manipulation Package

This package provides utilities for manipulating dates and times in JavaScript.

## Installation

You can install this package via npm. Make sure you have Node.js installed.

```bash
npm install datetime-manipulation
```

## Usage

### Importing the Package

You can import the package in your JavaScript/TypeScript files as follows:

```javascript
import { DateTimeUtils } from "datetime-manipulation";
```

### Available Methods

#### 1. `addDays(date: Date, days: number): Date`

This method adds the specified number of days to the given date.

#### 2. `subtractDays(date: Date, days: number): Date`

This method subtracts the specified number of days from the given date.

#### 3. `formatDate(date: Date, format: string): string`

This method formats the given date according to the specified format string. The format string follows the rules of the [Moment.js library](https://momentjs.com/docs/#/displaying/format/).

### Example

```javascript
import { DateTimeUtils } from "datetime-manipulation";

const today = new Date();
const tomorrow = DateTimeUtils.addDays(today, 1);
console.log("Tomorrow:", tomorrow);

const formattedDate = DateTimeUtils.formatDate(tomorrow, "YYYY-MM-DD");
console.log("Formatted Date:", formattedDate);
```

## Contribution

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This package is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
# time-manipulation
