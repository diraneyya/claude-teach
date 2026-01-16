## Usage

1. Download [`CLAUDE.md`](https://raw.githubusercontent.com/diraneyya/claude-teach/refs/heads/master/CLAUDE.md)
2. Drag and drop into your LLM chat window
3. Type in your prompt, which may look something like this:
    ```
    I want you to act as a teacher, a manual is provided in the attachments. Read it BEFORE you begin teaching.
    
    Today's topic is ...
      ⤷ I am interested in ...           (to help the LLM focus on what interests you)
      ⤷ So far I have used ...           (to help the LLM know what you already know )
      ⤷ I want a ... approach            (to help the LLM adapt to the desired style )
      ⤷ I am trying to eventually ...    (to have a blend of teaching/problem solving)
    
    The time I want to allocate for this learning session is ...
    ```

### Example

```text
I want you to act as a teacher, a manual is provided in the attachments. Read it before you begin teaching.

Today's topic is SSL certificates. I am interested in self-signed certificates and I want to learn how to create one. So far, I have used certificates without much understanding of how they work. I want a hands-on approach. I am trying to eventually configure **code-server** from Coder to use the certificate.

The time I want to allocate for this learning session is 1 hour.
```
