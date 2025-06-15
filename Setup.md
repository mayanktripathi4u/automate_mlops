
# Create Virtual Env.
Best practice is to create separate env for each Project.

```bash
conda create -n mlops_venv python==3.10

conda env list

conda activate mlops_venv
```

# Run the App
```bash
python app.py
```

```bash
kill -9 $(lsof -ti:5001)
```

# Configure CI-CD Pipeline
Set GitHub Secrets.
Refer [Notes](./notes.txt)

GitHub > Settings > Secrets & Variables > Actions > 

