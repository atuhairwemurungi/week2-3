Part one: envitonment dependency and management
created a new folder/ directory and named it ds_env
configured my github username and email, to sync github with vs code
Then, called the folder created earlier, so that all the work is in that folder.
Initialised a git repository for the folder; ds_env
Configured the default branch in github to be main, so that it is easier later to push from mian to main
created the virtual environment as required
Got an error, so i first confirmed that python is installed
Then i tried agin, without specifying the version and it was created
Activated the venv
Installed the required packages for data analysis.
i run: pip install pandas
i got a notice that pip needs an upgrade , so i upgraded it
i run: pip install matplotlib
i run: pip install seaborn
i run: pip install scikit-learn
i run: pip install scipy
i run: pip install numpy
Because pandas comes with numpy, it showed that the requirement is already satisfied.
To show all the packages that had been installed, i run: pip freeze > requirements.text
