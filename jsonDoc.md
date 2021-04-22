# JSON

---

## Brif Intro

- It stands for JavaScript Object Notation.
- A data representation format.
- Commonly used for creating & consuming APIs and Config files.

---

## Plus Points

- It is light weight and easy to read/write.
- Integrated easily with other languages(Python,Java,etc)

---

## Datatypes supported by Json

1. **Strings** ex: "name":"Andrew Lee"
2. **Numbers** ex: "age": 22
3. **Boolean** ex: "human": true
4. **Null** ex: "enemies":null
5. **Array** ex: "friends": ["Jhon","Reena","Justin","Brad"]
6. **Object** ex: "skills":{"html":"M","css":"M","javascript":"M","react":"B"}

**Imp. Note**

    : All Dataypes should be writen inside a Square Bracket {}, just like javascript object.
    : Key & Values should be writen in Double Quote " "
    : (Number, Boolean, Null) do not need "double quotes" while writing them as **Values**.

---

## JSON.parse()

When we receiving data from a web server, the data is always a string. Parse the data with JSON.parse(), and the data becomes a JavaScript object.
**Example:**
`'{ "name":"John", "age":30, "city":"New York"}'`
Use the JavaScript function **JSON.parse()** to convert text into a JavaScript object:-
`var obj = JSON.parse('{ "name":"John", "age":30, "city":"New York"}');`

## [Refrence:](https://www.w3schools.com/js/js_json_parse.asp)

## JSON.stringify()

    : A common use of JSON is to exchange data to/from a web server.
    : When sending data to a web server, the data has to be a string.
    : Convert a JavaScript object into a string with JSON.stringify().

`var obj = { name: "John", age: 30, city: "New York" };`
Use the JavaScript function **JSON.stringify()** to convert it into a string.
`var myJSON = JSON.stringify(obj);`
[Refrence:](https://www.w3schools.com/js/js_json_stringify.asp)

---

# Json Examples:

### 1

```
    {
  "myname": "Jack Rayn",
  "age": 22,
  "isIndian": true,
  "enemies": null,
  "friends": ["Ron", "Jacob", "Mathew", "Steve", "Hena"],
  "skills": {
    "html": "Moderate",
    "css": "Moderate",
    "javascript": "Moderate",
    "react": "Basic"
  }
}

```

### 2

```
    {
    "eBooks":[
        {
            "language":"Pascal",
            "edition":"third"
        },
        {
            "language":"Python",
            "edition":"four"
        },
        {
            "language":"SQL",
            "edition":"second"
        }
    ]
    }
```
