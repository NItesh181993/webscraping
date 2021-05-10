# webscraping
Webscraping using Node js 

What you need to run this app:

* [Node.Js](https://nodejs.org)

## Instructions

### Setup

* Clone this repo:
https://github.com/NItesh181993/webscraping.git



* Run this command:

```
npm install
```

### Running the code

### 1) Execute this command in your terminal:

```
node index.js

```

**2) URL for webscraping testing (Use Postman)**
```
http://localhost:3000/scrap 
```

3) **Use a Postman application then select a method as a "POST" and enter the above mentioned URL in the Url section in the Postman and then in body section select raw and change the text as JSON**.

  **Dont Forget to Add http or https before adding the url in the postman**
  ```
    In the Empty workspace add:
    {
      "url":"https://www.youtube.com"  //could use any other URL also
    }
  ```  
   Then click on Submit Button, you will see the output on the console below.
