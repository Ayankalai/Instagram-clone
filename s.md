 npm init  
  npm run dev  
   npm install express  { package.json ,"type": "module", import express}
   npm i dotenv
   npm i cors
   npm i -D nodemon


public => temp => .gitignore {ewbsite} gitignore generator => node copy


/*********************** RAPER FUNCTION **************************/

// const asynchandler = () =>  () => {}
// const asynchandler = () => ( () => {})
// const asynchandler = () => ( async() => {})


// const asynchandler = (fn) => async(req,res,next) => {
//     try {
//         await fn(req,res,next)
//     } catch (error) {
//         res.status(err.code || 500).json({
//             success: false,
//             massage: err.massage
//         })
//     }
// }