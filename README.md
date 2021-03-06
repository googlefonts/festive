It's Festive! But don't let the name fool you… It's a fun script font (plus a Roman) accompanied by an assortment of exciting ornamental dingbats suitable for any occasion where festivities abound— from New Years to Graduation, Baby & Wedding Showers, Thanksgiving, and much more— even Sports.

The base font works well with bodies of copy, while the alternate fonts can be used to swap out individual characters to give a custom, hand written look. Be sure to scroll thru to see all the stylistic sets.

The fonts in this family come complete with Latin Character sets including Western, Central, and Vietnamese language support.

## Building the Fonts

The font is built using fontmake and gftools post processing script. Tools are all python based, so it must be previously installed.

To install all the Python tools into a virtualenv, do the following:

From terminal:

```

cd your/local/project/directory

#once in the project folder create a virtual environment. 
This step has to be done just once, the first time:

python3 -m venv venv

#activate the virtual environment

source venv/bin/activate

#install the required dependencies

pip install -r requirements.txt

```

Then run the this command:

```
cd sources
gftools builder config.yml
```
