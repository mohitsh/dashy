# Rsbuild project


```



function → const
(props) → = (props) =>

function UserCard(props) {
    return <div>{props.name}</div>;
}



const UserCard = (props) => {
    return <div> {props.name} </div>;
}


userState: stores data that can change | "remember this data"

userEffect: runs cade at specific time | do this action when something happens

function handleClick() {
  setCount(count + 1);
}

onClick={handleClick}

onClick={() => setCount(count+1)}


```




## Setup

Install the dependencies:

```bash
pnpm install
```

## Get started

Start the dev server, and the app will be available at [http://localhost:3000](http://localhost:3000).

```bash
pnpm dev
```

Build the app for production:

```bash
pnpm build
```

Preview the production build locally:

```bash
pnpm preview
```

## Learn more

To learn more about Rsbuild, check out the following resources:

- [Rsbuild documentation](https://rsbuild.rs) - explore Rsbuild features and APIs.
- [Rsbuild GitHub repository](https://github.com/web-infra-dev/rsbuild) - your feedback and contributions are welcome!
