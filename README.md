# python-dictionary
>>> data={1:'pooji',2:'ashu',3:'vaishu',4:'hari',5:'sri'}
>>> data
{1: 'pooji', 2: 'ashu', 3: 'vaishu', 4: 'hari', 5: 'sri'}
****fetching values****
>>>data[1]
'pooji'
>>>y=data[2]
>>>print(y)
 ashu
 >>> data.get(3)
'vaishu'
>>> data.get(0)
>>> print(data.get(0))
None
>>> data.get(0,'no value')
'no value'
>>> data.get(4,'no value')
'hari'

****Adding keys and values to dictionary****

>>> keys=['pooji','malli']
>>> values=['singing','playing']
>>> data=dict(zip(keys,values))
>>> data
{'pooji': 'singing', 'malli': 'playing'}
>>> data['madhu']='cooking'
>>> data
{'pooji': 'singing', 'malli': 'playing', 'madhu': 'cooking'}
>>> del data['madhu']
>>> data
{'pooji': 'singing', 'malli': 'playing'}

****list and dictionary inside the dictionary****

>>> prog={'js':'atom','cs':'vs','python':['sublime','pycharm'],'java':{'jse':'netbeans','jeee':'eclipse'}}
>>> prog
{'js': 'atom', 'cs': 'vs', 'python': ['sublime', 'pycharm'], 'java': {'jse': 'netbeans', 'jeee': 'eclipse'}}
>>> prog['js']
'atom'
>>> prog['python'][0]
'sublime'
>>> prog['python']
['sublime', 'pycharm']
>>> prog['java']
{'jse': 'netbeans', 'jeee': 'eclipse'}
>>> prog['java']['jse']
'netbeans'
----end----


 
