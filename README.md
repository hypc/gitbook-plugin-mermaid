# gitbook-plugin-mermaid

[mermaid][] for gitbook.

## Install

You can install via npm:

```shell
$ npm install https://github.com/hypc/gitbook-plugin-mermaid.git
```

And use it for your book with the `book.json`:

```json
{
    "plugins": [{
        "name": "mermaid",
        "version": "git+https://github.com/hypc/gitbook-plugin-mermaid.git"
    }]
}
```

## Usage

You can use it like this:

    ```mermaid
    graph TD;
        A-->B;
        A-->C;
        B-->D;
        C-->D;
    ```

And you can get more synax in [here][mermaid].


[mermaid]: https://github.com/knsv/mermaid

