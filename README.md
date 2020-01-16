# Contains my learing from Python

### Not able to post body to your flask app from your swagger ui docs endpoint.

Try to add CORS

```bash

from flask_cors import CORS

app = Flask(__name__)
CORS(app)
```

