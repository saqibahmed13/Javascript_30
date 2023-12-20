# Javascript_30

Implement a function that converts a Javascript value into a JSON string.

   function convertToJson(value){
    const result  = JSON.stringify(value);
    return result;
     }
     const obj = {
     name: "saqib",
     age:"24",
     mail:"noreply@gmail.com"
   };
   console.log(obj);
   const jSonValue = convertToJson(obj);
   console.log(jSonValue);

