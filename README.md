Aeroo Reports
=============

Aeroo Reports for Odoo

Allows the generation of Aeroo reports

安装依赖
git clone https://github.com/adhoc-dev/aeroolib.git -b master-fix-ods
cd aeroolib
sudo ./setup.py install

pip3 install git+https://github.com/aeroo/currency2text.git

git clone https://github.com/OCA/report-print-send.git -b 16.0

sudo apt update
sudo apt-get install libcups2-dev
pip3 install pycups
