# Book Retrieval System (SI 650)

## How to run
The current project will need to be run using an IDE or the command line.

##### Clone the current repository to your local machine
        git clone https://github.com/miscalculation/Book-Retrieval-System.git
        
##### Install a virtual enviroment project4-env
        python3 -m pip install --user virtualenv    # For Mac/Linux...
        py -m pip install --user virtualenv    # For Windows

##### Create a new virtual environment called venv (will be in current folder)
        py -m venv venv    # For Mac/Linux... 
        python3 -m  venv venv     # For Windows
    
##### Activate project4-env
        source venv/bin/activate    # For Mac/Linux...
        venv\Scripts\activate    # For Windows
        (venv) # you've succeeded if you see this after!
        
##### Install all packages based on a list in a file called requirements.txt
        (venv) pip install -r requirements.txt

##### Run program
        flask run
        
##### Copy and paste the localhost base URL to a browser and add "/book" to the end
        Some localhost URL examples could be http://localhost:5000/book or http://127.0.0.1:5000/book
        Please make sure there is internet connection if the cache file is not in place. Google chrome may not work. Edge usually work for this application
        You should see a page like this:
        ![alt text](https://github.com/miscalculation/Book-Retrieval-System/blob/master/BookSite.png?raw=true)
        
        
##### Deactivate the virtual environment
        (venv) deactivate
