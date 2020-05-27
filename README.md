Result of following a [LoginWithBulma tutorial](https://github.com/websharper-samples/LoginWithBulma) introducing to WebSharper.

Also - reproducing an autoformatting issue within VSCode.

To reproduce:

- first check that you're able to `dotnet run` successfully
- open `Client.fs`
- `alt + shift + f`
- `dotnet run`

The last command results in the following error:

```
C:\source\websharper-samples\LoginWithBulmaTutorial\Client.fs(26,17,34,53): parse error FS0597: Successive arguments should be separated by spaces or tupled, and arguments involving function or method applications should be parenthesized [C:\source\websharper-samples\LoginWithBulmaTutorial\LoginWithBulmaTutorial.fsproj]

The build failed. Fix the build errors and run again.
```