import sys
import os
import unittest
import sys
sys.path.insert(0,os.path.abspath(os.path.join(os.path.dirname(_file) + '/src')))
sys.path.insert(0,os.path.abspath(os.path.join(os.path.dirname(_file) + '/tests')))
from core import main
if name = 'main':
    f=open('packets/tcp.txt','r')
    g=open('packets/udp.txt','r')
    main(f)
