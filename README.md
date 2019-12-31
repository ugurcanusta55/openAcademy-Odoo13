# openAcademy-Odoo13

### Odoo 13 works with python3.6 or above

#### To Run Module Firstly install odoo13 via github
```git clone https://github.com/odoo/odoo.git```

#### For Create virtualenv
```python3.6 -m venv myodovenv```

```source myodovenv/bin/activate```

#### For İnstall requirements
```pip install -r requirements.txt```

#### Copy Module to Addons
```cp -r openAcademy-Odoo13 ./addons```

#### For Run Odoo Project
```python odoo-bin -r "odoo" -w 'odoo123'  --addons-path=addons/```

##### Then Open Odoo and Search openAcademy module and Install it
