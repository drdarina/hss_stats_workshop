# Installation

You can follow along just looking at the screen. However, if you want to run the code yourself, you need to first set up the envrionment. These installation steps are for Linux. I don't have much experience with Windows/Mac systems, but the setup is very straighforward and Google should help you out.

I assume that you already have python, pip and jupyter lab and that you are online.

1. Install pipenv

`pip install pipenv`

(You can use a different package manager if you prefer, just install the dependencies from Pipfile!)

2. In the workshop folder, run

`pipenv install`

to install the packages needed to run the notebooks.

3. Make a jupyter kernel for the workshop

`pipenv run ipython kernel install --name "stats-workshop" --user`

4. Start up jupyter and select stats-workshop as kernel.

Note that instead of doing step 3-4, you can also execute `pipenv run jupyter lab` from the workshop folder.

5. Open the "test_setup.ipynb" notebook and run the two cells. If they run without issues, your environment works correctly.
