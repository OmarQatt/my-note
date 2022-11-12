# Chakra UI


## What is a Chakra UI?
Chakra UI is a simple, modular and accessible component library that gives you the building blocks you need to build your React applications.

## Is Chakra UI better than material UI?
-Chakra UI provides easy manual manipulation in CSS classes, whereas Material UI makes it much harder to customize its components
-currently easier to pick up controls from it
## How to use Chakra UI?

To use Chakra UI in your project, run one of the following commands in your terminal:
npm i @chakra-ui/react @emotion/react @emotion/styled framer-motion
yarn add @chakra-ui/react @emotion/react @emotion/styled framer-motion
pnpm add @chakra-ui/react @emotion/react @emotion/styled framer-motion

After installing Chakra UI, you need to set up the ChakraProvider at the root of your application.
This can be either in your index.jsx, index.tsx or App.jsx depending on the framework you use.

```
import * as React from 'react'

// 1. import `ChakraProvider` component
import { ChakraProvider } from '@chakra-ui/react'

function App() {
  // 2. Wrap ChakraProvider at the root of your app
  return (
    <ChakraProvider>
      <TheRestOfYourApplication />
    </ChakraProvider>
  )
}
```
