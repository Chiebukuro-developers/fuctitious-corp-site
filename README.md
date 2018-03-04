# Training WEB site for Abenosan

## How to Install
### Windows
1. open the command prompt or the windows powershell
2. move to working directory
3. type under code
    ```
    git clone https://github.com/Chiebukuro-developers/TrainingWeb.git
    ```

### Mac or Linux
1. open the terminal
2. move to working directory
3. type under code
    ```
    git clone https://github.com/Chiebukuro-developers/TrainingWeb.git
    ```

## Develop Guideline
### Commit
- please follow the commit format when you commit
#### Commit Format
```
(type)((scope)): (brief commit message)

(detail of commit)

Issue #(Issue No)
```

#### Commit types
- `feat`: when you add new handler and so on
- `fix`: when you fix bug
- `docs`: when you edit document or add new document
- `style`: when you change design(css and so on)
- `refactor`: when you change existing code
- `perf`: when you change code for increased performance

#### Scope
- please write files or place affected by commit
- if you have any files affected by commit, please use `*`

#### example
```
style(header): change style of logo

change width and heaight of the logo in header

Issue #3
```