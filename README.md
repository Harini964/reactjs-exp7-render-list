![WhatsApp Image 2025-09-11 at 13 22 40_714d0b4d](https://github.com/user-attachments/assets/283534da-bc28-4cc4-a2c1-1545a154236f)


## Student List Rendering Example

This project demonstrates **list rendering in React with Vite**.  
A list of student names is displayed dynamically using the `map()` function, with each list item assigned a unique `key` prop.

### Screenshot
Below is a screenshot of the app running on `http://localhost:5173/`:

![Student List Screenshot](./WhatsApp%20Image%202025-09-11%20at%2013.23.39_12865585.jpg)

### Explanation
- A predefined array of students (`Mahesh, Gani, Harini, Sai`) is stored in the component.  
- Using the `map()` function, each student is rendered as an `<li>` element.  
- The `key` prop ensures that each list item is uniquely identifiable by React.  
- Example code:  
  ```jsx
  {students.map((student) => (
    <li key={student.id}>{student.name}</li>
  ))}
