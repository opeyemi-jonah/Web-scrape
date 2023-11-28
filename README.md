Windows setup:
    pip install virtualenv
    
    Navigate to the folder you want to create the virtual environment, and start virtualenv.
        cd /scrapy_tutorials
        virtualenv venv
    
    Activate the virtual environment.
    source venv\Scripts\activate <-- Won't work on windows. Use forum (https://forum.freecodecamp.org/t/cannot-activate/557438/4) to find solution.

    ./venv/Scripts/activate.bat <-- This worked for me.

    pip install --user scrapy
   
    