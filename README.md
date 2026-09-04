# React application stack for Kubernetes on Wodby

Deploy React applications on Kubernetes with [Wodby](https://wodby.com).

## Stack contract

- [React stack on Wodby](https://wodby.com/stacks/react)
- [React service](https://github.com/wodby/service-react)
- [React boilerplate](https://github.com/wodby/react-boilerplate)
- [Wodby stack documentation](https://wodby.com/docs/2.0/stacks/)

The stack contains one required main service. The React service inherits the Nginx runtime and exposes the React starter as its boilerplate.

## Validate the manifest

```sh
wodby stack validate-manifest stack.yml --org <org-id>
```

See the [stack manifest reference](https://wodby.com/docs/2.0/stacks/template/) and [managed stacks index](https://github.com/wodby/stacks).
