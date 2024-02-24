# Pagination documents old verstion  and new verstion added !!! wow !!!!
// external code

```js
import React from 'react';

const App = () => {
  return (
    <div className='w-11/12 lg:max-w-7xl m-auto py-2'>
     <div className='grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8'>
     { [...Array(8).keys()].map(d=>{
       return  <div className="border animate-pulse p-2 rounded-md">
       <div className="bg-[#DDDDDD] w-[264px] h-[178px] rounded-md">
       </div>
       <div>
         <div className="py-3">
           <h1 className="w-[150px] h-[25px] rounded-md bg-[#DDDDDD]"></h1>
           <h1 className="w-[100px] mt-1 h-[15px] rounded-md bg-[#DDDDDD]"></h1>
         </div>
         <div className="flex justify-between">
         <button className="py-4 px-10  bg-[#DDDDDD] rounded-sm"></button>
         <button className="py-4 px-10  bg-[#DDDDDD] rounded-sm"></button>
         </div>
       </div>
        </div>
       })}
     </div>
    </div>
   

  );
};

export default App;
```
