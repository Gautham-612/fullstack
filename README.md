import React,{useState} from 'react'

export default function Home() {
    const [name,setName]=useState({fname:'vivek'})
    const change=()=>{setName({fname:'sam'});}
  return (
    <div>
    <h1>Welcome {name.fname}</h1>
     <button onClick={change}>ChangeName</button>
    </div>
  )
}
