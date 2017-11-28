.. _undefined.Engine:

=================
Class: ``Engine``
=================


.. contents:: Local Navigation
   :local:

Children
========

.. toctree::
   :maxdepth: 1
   
   
Description
===========

<p>Create the Engine.</p>


.. _module-cicero-engine.Engine.compileClause:


Function: ``compileClause``
===========================

<p>Compile and cache a clause</p>

.. js:function:: compileClause(clause)

    
    :param Clause clause: <p>the clause to compile</p>
    
.. _module-cicero-engine.Engine.buildDispatchFunction:


Function: ``buildDispatchFunction``
===================================

<p>Generate the runtime dispatch logic</p>

.. js:function:: buildDispatchFunction(clause)

    
    :param Clause clause: <p>the clause to compile</p>
    :return string: <p>the Javascript code for dispatch</p>
    
.. _module-cicero-engine.Engine.execute:


Function: ``execute``
=====================

<p>Execute a clause, passing in the request object</p>

.. js:function:: execute(clause, request)

    
    :param Clause clause: <p>the clause to execute</p>
    :param object request: <p>the request, a JS object that can be deserialized<br>using the Composer serializer.</p>
    :return Promise: <p>a promise that resolves to a result for the clause</p>
    

.. _module-cicero-engine.Engine.scripts:

Member: ``scripts``: 

.. _module-cicero-engine.Engine.scripts[undefined]:

Member: ``scripts[undefined]``: 




