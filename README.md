#link - https://pybuilder.io/
"# python-pybuilder-repo-structure" 

#For New REPO
  #!/bin/sh

  pip install pybuilder

  If you want the bleeding edge
  (we release after every commit)
  pip install --pre pybuilder

  pyb --start-project
  pyb publish
  
  
  #For Existing repo
  
  git clone https://github.com/twentybn/GulpIO
  cd GulpIO
  python -m venv venv
  source venv/bin/activate
  pip install pybuilder

  If you want the bleeding edge
  (we release after every commit)
  pip install --pre pybuilder

  pyb


