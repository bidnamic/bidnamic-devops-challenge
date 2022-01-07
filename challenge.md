<img src="logo.png" alt="drawing" width="500"/>

## DevOps / SRE Challenge

Here is a minimal flask app:

```python
from flask import Flask
app = Flask(__name__)

@app.route('/')
def pretend():
    return 'Lets pretend this function eats lots of resources!'
```


### Task
1. Deploy this flask app to AWS using Terraform.


2. Consider the  following through your code or your README.

    ```text
    - Packaging
    - Deployment
    - Security
    - Monitoring
    - Scaling
    - Troubleshooting
    ```


### Submission

Please fork this repo to complete the challenge, once done email back link to your repo.

Good luck we are rooting for you!