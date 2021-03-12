# Dates and times

[info] **Highlight:** Use the *day of week, month dd, year* date format to express dates. Express time in the 12-hour format and always include *AM* and *PM*. Use Coordinated Universal Time (UTC) and always include the time zone for real times. [/info]  

In general, spell out months and days whenever possible. Use the *day of week, month dd, year* date format. For example, use *Sunday, August 16, 2020*. Express time in the 12-hour format, capitalize AM and PM, and include the time zone.

Expressing dates and times in a clearly defined manner reduces confusion and improves translation support for a [global audience](https://make.wordpress.org/docs/style-guide/general-guidelines/global-audience/).

## Expressing times

Use the following guidelines to express time:
- Express time in the 12-hour format. Use the 24-hour format only when absolutely needed. If a particular UI, statement or code example uses the 24-hour format, then use that format throughout the page for consistency.
- Use numerals to express times of the day.
- Always include *AM* and *PM*. Insert a space between the time and *AM* or *PM* and ensure that it is capitalized.  
  **Example**  

  [tip] **Recommended:** 4:32 PM, 12:00 PM, 7:15 AM. [/tip]  

- For time ranges, use the word *to* instead of the en dash. Use an en dash with no surrounding spaces for a schedule or listing.  
  **Examples**  

  [tip] **Recommended:** The server was down from 3:00 AM to 5:00 AM. [/tip]  
  [tip] **Recommended:** The meeting is scheduled from 15:00–16:00 UTC. [/tip]  

  **Exception:** For date ranges consisting of two dates and times, use an en dash with spaces surrounding the dash.  
  **Examples**  

  [tip] **Recommended:** 7:30 AM–9:15 AM 05/11/2020 (time range on a single day) [/tip]  
  [tip] **Recommended:** 7:30 AM 04/11/2020 – 9:15 AM 05/11/2020 (date and time range) [/tip]  
- It is acceptable to remove the minutes from round hours.  
  **Example**  

  [tip] **Recommended:** 4 PM. [/tip]  
- Using *noon* and *midnight* is acceptable, but not when paired with time in the numeral format.  
  **Example**  

  [warning] **Not recommended:** *12:00 noon, 12:00 midnight* [/warning]  

### Time zones

Generally, include the time zone if your documentation influences a global audience. Otherwise, avoid using time zones unless absolutely necessary, where excluding them would cause confusion. You don't need to include the time zone where the reader's local time is shown automatically.

Use the following guidelines to express time zones:
- Capitalize time zones. Don't abbreviate them unless absolutely needed.
- Specify the spelled-out time zone region and then the UTC or GMT offset in parentheses. Don't insert spaces around the hyphen (-) or plus sign (+).  
  **Examples**  

  [tip] **Recommended:** US Eastern Time (UTC-05:00) [/tip]  
  [tip] **Recommended:** Indian Standard Time (UTC+05:30) [/tip]  
- If the time is the reader's local time, indicate it accordingly.  
  **Example**  

  [tip] **Recommended:** The weekly team meeting will start at 7:30 PM your local time. [/tip]  
- Use Coordinated Universal Time (UTC) over Greenwich Mean Time (GMT), in general. Don't write *Universal Time Coordinate* or *Universal Time Coordinated* as alternatives to Coordinated Universal Time. Only use GMT unless absolutely needed.
- For time zones without names, use the Coordinated Universal Time (UTC) offset. If you're writing about a particular geographic area, specify the country or region if UTC is unavailable.  
  **Examples**  

  [tip] **Recommended:** UTC+7 [/tip]  
  [tip] **Recommended:** Standard Time (Fiji) [/tip]    
- Don't specify *standard time* or *daylight saving time* unless specifically writing about them. When the time doesn't change for daylight saving time, use the specific time zone without reference to UTC.

## Expressing dates

Spell out the names of months and days of the week. Write the full four-digit year, rather than a two-digit abbreviation. If including the day of the week, add it before the month and insert a comma after it. Capitalize the first letter of the days of the week and months. Use the *day of week, month dd, year* format.  

Don't use ordinal numbers to indicate a date.

**Examples**  

[warning] **Not recommended:** August 16th 2020 [/warning]  
[tip] **Recommended:** August 16, 2020 [/tip]  
[tip] **Recommended:** Sunday, August 16, 2020 [/tip]  

### Abbreviated and partial dates

While indicating only the month and year in a date, don't use a comma.

**Example**  

[tip] **Recommended:** The latest version was released in May 2020. [/tip]  

Don't abbreviate the days of the week or the month unless absolutely necessary, although abbreviating is acceptable in UI, tables, or headings where space is limited. Abbreviate the days of the week to three-letter abbreviations like *Sun, Mon, Tue, Wed, Thu, Fri*, and *Sat* and the month to three-letter abbreviations such as *Jan, May*, and *Sep*. Capitalize the first letter and don't insert a period at the end of the abbreviation.

If you abbreviate, do so for the entire date. Don't combine written-our forms with abbreviated forms in the same date.

Be consistent with your abbreviations throughout your documentation. For example, if you abbreviate dates in UI or tables, ensure that all subsequent instances of dates in UI or tables are abbreviated similarly.

**Examples**  

[warning] **Not recommended:** Mon, November 24, 2020 [/warning]  
[tip] **Recommended:** Mon, Nov 24, 2020 [/tip]  

### Dates in the middle of a sentence

When indicating dates in the *month dd, year* format in the middle of a sentence, insert a comma after the year. However, if the date in the middle of the sentence consists of only the month and year, then don't insert a comma after the year.

**Examples**  

[tip] **Recommended:** It was only until May 4, 2020, that the latest version was released. [/tip]  
[tip] **Recommended:** It was only until May 2020 that the latest version was released. [/tip]  

### Numerical dates

Only express dates in the numerical format unless absolutely required. When indicating dates in a numerical date format, use the [ISO 8601 international standard](https://wikipedia.org/wiki/ISO_8601) date format *YYYY-MM-DD*. Separate the year, month and day using hyphens.

Additionally, if you have a choice of what date to write (such as in a fictional example), then choose a calendar day greater than 12 to differentiate it from the month.

### Things to avoid while expressing dates

Generally, don't express months as numerals, as the numerical date format is varied in different parts of the world.
For example, the date 01/02/20 is interpreted differently in different regions:
- In the British date format, 01/02/20 means February 1, 2020. Here, the order is *day, month, year*.
- In the American date format, 01/02/20 means January 2, 2020. Here, the order is *month, day, year*.
- In date formats of some other regions, 01/02/20 means 20 February, 2001. Here, the order is *year, month, day*.

Hence, expressing dates in the numerical format may be confusing for a global audience. To avoid confusion, generally express dates in words.

**Examples**  

[warning] **Not recommended:** 01/02/20 or 01/02/2020 [/warning]  
[warning] **Not recommended:** 01.02.20 or 01.02.2020 [/warning]  
[warning] **Not recommended:** 01-02-20 or 01-02-2020 [/warning]  
[tip] **Recommended:** January 2, 2020 [/tip]  
[tip] **Recommended:** Thursday, January 2, 2020 [/tip]  

## Seasons and divisions of the year

Avoid referring to seasons, as all regions around the world don't have similar seasons and global audiences may find it difficult to correspond them to calendar months. For example, winter in the northern hemisphere is summer in the southern hemisphere. Instead of seasons, use months or calendar quarters.

**Examples**  

[warning] **Not recommended:** During winter, you may encounter delays in responses due to staff holidays.  [/warning]  
[tip] **Recommended:** During December, you may encounter delays in responses due to staff holidays. [/tip]  

[warning] **Not Recommended**: All major versions are released in the fall of each year. [/warning]  
[tip] **Recommended:** All major versions are released in October of each year. [/tip]  

If you must mention a specific season, identify either the hemisphere or region, or both. Don't capitalize the season, except while designating the issue of a publication. For example, *Fall 2021*.
