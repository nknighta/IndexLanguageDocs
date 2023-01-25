# Welcome to il!

## about il
### based...
    front end 
        - Typescript(ES6)
        - Javascript
        - HTML
    middleware
        - php
        - java(?)
    backend
        - C++
        - Rust
        - wasm(?)
    globalConfigulation
        - yaml or json or *.config.js
## Hello world
```
fn main(){
    p! |"Hello il"|;
}
```


## make frontend + middleware + backand sample(X_X;)
```
exp fn subpropExample:Mode<C,U>: () {
    int title = 'aaaa';
    string ca = p! => | "Hello!" |   <- this is Option
    int count = (() => {
        int count2 = count2 + 1
    },()) 
    return (
        <>
            <h1>{title}</h1>
            <h2>{ca}</h2>
            <button script={count.count2}>
        </>
    )
}

exp fn privatePropsExample:Mode<C>: {

}

autofor(roop) protomodel
fn AutoForExample:Mode<C>: (count){
    roopd (count < 6) :: count = count++;
}

fn AutoForExample extend Interface.React:Mode<C>: (count){
    roopd (count < 6) :: count = count++;
    return<htmld>(
        <>
            <button ? : click = {count}>Push!</button>
            <p>button push count >>> ${return (count)} max int of 6</p>
        </>
    )
}
```

Mode is
| Mode | type |
| --- | --- |
| U | frountend(based HTML5) |
| M | middle ware(based php , NodeJS and TS from ES6) |
| C | control of backend(based C++ or Rust) |


```
fn subpropExample:Mode<Auto>: ({title}) {
    title = 'aaaa';
}
```

```
exp int valueSample = 1;

exp auto valueSample Interface.React : () : {
    string title = ' Hello il!'
    return<Reactd>(title)
};
```

```ts
type TestValueProps = {
    title: string
}

export const TestValueSampleJS:React.FC<TestValueSample> = ({title}) =>{
    return(
        <>
            <p>{title}</p>
        </>
    )
}
```

3rd party library import sample
- 3rd party import sample(type R version Proto first)
```
import { Reactd } from "@type-il/react"

exp auto valueSample Interface.React : () : {
    string title = ' Hello il!'
    return<Reactd>(title)
};

```

- 3rd party import sample(type L version C)
```yaml
AssetsConfig:
    list:
        U:
            Reactd: - v0.1.20
            htmld: - v0.1.11
        C: 
            gcc-il: -v0.2.11
    sublist:
        gcc-il-type: -v0.3.5
```
▽▽▽▽▽▽▽▽▽▽

auto load library from assets.yaml

▽▽▽▽▽▽▽▽▽▽
```
exp auto valueSample Interface.React : () : {
    string title = ' Hello il!'
    return<Reactd>(title)
};

```