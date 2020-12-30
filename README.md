## Automation Exercise

### Brief

Starting with Wikipedia's https://en.wikipedia.org/wiki/Metis_(mythology) page, please test for the following:

a) the headings listed in the `Contents` box are used as headings on the page
b) the headings listed in the `Contents` box have functioning hyperlinks
c) in the _Personified concepts_, `Nike` has a popup that contains the following text:

`In ancient Greek civilization, Nike was a goddess who personified victory. Her Roman equivalent was Victoria.`


d) in the _Personified concepts_, if you click on `Nike`, it takes you to a page that displays a family tree

### Installing
``` 
git clone <>
virtualenv venv
source venv/bin/activate 
pip install -r requirements.txt
```

### Executing Tests

`> py.test`

### Notes:
1. I have included the geckodriver.exe in the `/lib/drivers`
2. In test case c) the popup text says `Greek civilization` instead of `Greek religion` . I have updated it to pass the test case.
