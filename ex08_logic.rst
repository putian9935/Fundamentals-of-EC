实验八 组合逻辑电路
=====================================


半加器实现

用与非门实现

.. math:: C = AB = \overline{\overline{AB}} =  \overline{\overline{AB}\,\overline{AB}}

.. math:: S = A \overline{B} + \overline{A}  B = \overline{\overline{A\overline{B}} \,\overline{\overline{A}  B }}

而

.. math:: A \overline{B} = A \overline{B}  + A \overline{A} = A \overline{AB}

这样，

.. math:: S = \overline{\overline{A \overline{AB}} \,\overline{\overline{AB}  B }}

电路图
-------------



