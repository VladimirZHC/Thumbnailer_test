Test Django app where user puts image and get zip file that contains zip file with image 128x128
Make sure that you install Redis:
  use https://redis.io/download and then:
  1.write 'redis-server' in command line to run your server(you can split your terminal and in second terminal write 'redis-cli to make sure that all works).
  2.after all go to your project(where manage.py contains) and write 'celery -A image_parroter worker' to connect your app with port 6379.
  
 
