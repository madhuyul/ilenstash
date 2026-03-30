# Setting Up Django on Windows

## Prerequisites
1. **Python**: Make sure you have Python installed. You can download it from the [official Python website](https://www.python.org/downloads/).

2. **Django**: Use pip to install Django. Open your command prompt and execute:
   ```bash
   pip install django
   ```

3. **Database (Optional)**: Depending on your project requirements, you may need to set up a database. For SQLite, no additional setup is required.

## Step-by-Step Instructions

### 1. Create a Django Project
Open your command prompt and navigate to the directory where you want to create your project. Execute:
```bash
django-admin startproject myproject
cd myproject
```

### 2. Configure Server Name and Port
In your Django settings file (usually found in `myproject/settings.py`):
- Find the `ALLOWED_HOSTS` list and add your server name:
   ```python
   ALLOWED_HOSTS = ['your-server-name.com']  # Change this to your server name
   ```

- Set the port when you run your server. The default port is `8000`, but you can change it when you run the server. For example, use `runserver 8080` to run on port `8080`.

### 3. Run the Development Server
To start the development server, run:
```bash
python manage.py runserver
```
If you want to specify a port, you can do so:
```bash
python manage.py runserver 8080
```

### 4. Access the Application
Open your web browser and navigate to:
- `http://localhost:8000/` or `http://localhost:8080/` (if you changed the port).

## Conclusion
You now have a basic Django application running on your Windows machine. You can further customize the settings and start building your application!