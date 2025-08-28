# Example: Install dependencies for your test runner
pip install -r requirements.txt
# Example command using a test runner
locust -f locustfile.py --headless -u [num_users] -r [spawn_rate] --run-time [duration] --host [hostname]
