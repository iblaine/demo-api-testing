```
python -m venv myenv
source myenv/bin/activate
pip install -r requirements.txt


docker build --no-cache -t uptime-api .
docker run -p 5001:5000 uptime-api

curl http://localhost:5001/uptime
{"uptime":1716010431.8023264}

```
