# Review Checklist:
1. Check that handlers have input validation
2. Check that there are unit tests for newly added code
3. Check that test coverage does not go down
4. Check that any new endpoint is properly documented
5. Check that the new [errors package](https://github.com/addigy/errors) is being used
6. Make sure that you are returning the entire `Error` object when returning an error response, instead of a `string`.
7. Check that repo is migrated to the latest [CI/CD Platform](https://docs.google.com/document/d/1hzi4H7HXEfV1Pk9BP-k9fQTFRnVC9WNyuGQJjY4wyfE/edit?usp=sharing)

**Please write a brief and detailed description of what this PR is trying to accomplish**
