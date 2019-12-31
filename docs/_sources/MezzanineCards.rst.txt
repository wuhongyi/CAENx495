.. MezzanineCards.rst --- 
.. 
.. Description: 
.. Author: Hongyi Wu(吴鸿毅)
.. Email: wuhongyi@qq.com 
.. Created: 一 12月 31 09:45:30 2018 (+0800)
.. Last-Updated: 二 12月 31 17:27:05 2019 (+0800)
..           By: Hongyi Wu(吴鸿毅)
..     Update #: 3
.. URL: http://wuhongyi.cn 

##################################################
扩展子板
##################################################


============================================================
User FPGA I/O ports
============================================================

This section illustrates the I/O ports of the UFPGA. Port names are the same of the VHDL entity top-level ports used in the template and demo firmware.




============================================================
User's Code
============================================================

----------------------------------------------------------------------
G port
----------------------------------------------------------------------

输入输出控制：

.. code:: vhdl

   -- 输入
   nOEG <= '1';

   -- 输出
   nOEG <= '0';
	  

NIM/TTL选择控制：

.. code:: vhdl

   -- NIM
   SELG <= '0';

   -- TTL
   SELG <= '1';


	  
.. 
.. MezzanineCards.rst ends here
