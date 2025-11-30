# Set up

.env setup

```
SUPABASE_URL=https://your-supabase-url.supabase.co
SUPABASE_SECRET_KEY=your-anon-key
ELEVENLABS_API_KEY=your-elevenlab-api-key
```

Create Virtual Environment use Python 3.11

```
python -3.11 -m venv venv
```

Activate Virtual Environment (Linux And Mac)

```
source .venv/bin/activate
```
Activate Virtual Environment (Window)

```
venv/Scripts/activate
```

Install Dependencies

```
pip install -r requirements.txt
```

If you add more dependencies to the project use this command to update requirements.txt

```
pip freeze >> requirements.txt
```

Run to test 

```
python main.py
```
type model and the classifer will start


# Run as a service

```
fastapi dev server.py
```

#model
```
https://drive.google.com
```

#User Interface
```

```