# Syllabus for Frontend

## Week 01 - Basics:

- Learn the basics of React
    - **Props passing** : [https://legacy.reactjs.org/docs/components-and-props.html](https://legacy.reactjs.org/docs/components-and-props.html)
    - **Passing of data from Children to parent**
        - [https://blog.devgenius.io/how-to-pass-data-from-child-to-parent-in-react-33ed99a90f43](https://blog.devgenius.io/how-to-pass-data-from-child-to-parent-in-react-33ed99a90f43)
    - **Conditional Rendering**
        - [https://react.dev/learn/conditional-rendering](https://react.dev/learn/conditional-rendering)
    - **Hooks:**
        - useState() : [https://react.dev/reference/react/useState](https://react.dev/reference/react/useState)
        - useRef() : [https://react.dev/reference/react/useRef](https://react.dev/reference/react/useRef)
        - useMemo() : [https://react.dev/reference/react/useMemo](https://react.dev/reference/react/useMemo)
        - useEffect() : [https://react.dev/reference/react/useEffect](https://react.dev/reference/react/useEffect)
        - useQuery() : [https://builtin.com/software-engineering-perspectives/use-query-react](https://builtin.com/software-engineering-perspectives/use-query-react)
        - useContext() : [https://react.dev/reference/react/useContext](https://react.dev/reference/react/useContext)
    - **AuthContext**:
        - Making AuthContext so people without logging in cannot access forbidden routes.
    - **Routing:**
        - **For React:**
            - We will use react-router-dom
            - Making routes and secure some routes using AuthContext
            - Making Success/Error Routes
            - Making 404 Route
        - **For Next:**
            - Using App Router : [https://nextjs.org/docs/app/building-your-application/routing](https://nextjs.org/docs/app/building-your-application/routing)
            - Go through all the subtopics of Routing
    - **Directory Structure** i.e how to manage files in frontend and how to divide your code in into small size components
    - **Practices to learn :**
        - Divide and Conquer : If the one piece of code is not working with large part of code, separate that piece of code and work on it at smaller scale instead of working it with at large scale.
        - Use Null protection so that the program never crashes.
        - While writing the code, always create a variable with default values and use them instead of hard-coding them in code.
        - Always document your code with comments like
            - **`@param`** is used to document parameters and their types for function
            - **`@returns`** is used to document the return type and what the function returns.
            - **`@author`** Used to specify the author or authors of the code.
            - **`@description`** Provides a detailed description of the code element.
            - **`@see`** References other parts of the code, external resources, or related information.
            - **`@deprecated`** Marks a code element as deprecated, indicating that it is no longer recommended for use.
            - **`@example`** Provides usage examples for the code element.

---

## Week 02 - Backend Integration:

- **Axios:**
    - Installing and working with Axios
    - [https://axios-http.com/docs/example](https://axios-http.com/docs/example)
- **Sending Request** to specific API endpoint and console the results to determine output structure.
- **Codes:**
    - Working with response codes :
        - 200 OK Code
        - 400 error Code
        - 500 server error code
    - Handling the errors and statuses and displaying appropriate error message or success to the user.
- **Handling:**
    - Handling the output and displaying it at appropriate place.
    - Incase of no output, showing appropriate message to user
    - Adding loading and not loading states

---

## Week 03 - CSS Basics & Frameworks:

- **CSS Basics:**
    - Position of Elements: [https://www.w3schools.com/css/css_positioning.asp](https://www.w3schools.com/css/css_positioning.asp)
    - Box Model: [https://www.w3schools.com/css/css_boxmodel.asp](https://www.w3schools.com/css/css_boxmodel.asp)
    - Selectors: [https://www.w3schools.com/css/css_selectors.asp](https://www.w3schools.com/css/css_selectors.asp)
    - Flexbox: [https://www.w3schools.com/css/css3_flexbox.asp](https://www.w3schools.com/css/css3_flexbox.asp)
    - Grid: [https://www.w3schools.com/css/css_grid.asp](https://www.w3schools.com/css/css_grid.asp)
- **CSS Frameworks:**
    - Tailwind CSS : [https://tailwindcss.com/](https://tailwindcss.com/)
    - ChakraUI : [https://chakra-ui.com/getting-started](https://chakra-ui.com/getting-started)
        - Setting up the Chakra with NextJS & ReactJS
        - Learn these Chakra components along with their props:
            - VStack, HStack, Stack
            - Box
            - Text, Heading
            - Icon
            - Button
            - Loading states
            - Spinner
            - Drawer, Modal
            - List, List-items
            - Making design responsive using arrays
        - Chakra Hooks:
            - useDisclosure
            - useToast
