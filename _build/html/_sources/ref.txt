#######################
Object Reference
#######################

The ``HelloWorld`` namespace is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. 

- Assembly: HelloWorld.dll version 4.0125
- Download: http://ironsoftware.com/downloads/packages/helloworld.latest.zip
- Nuget: ``PM> install HelloWorld``


*******
Classes
*******

----------


HelloWorldRunner Class
======================

- Namespace: HelloWorld

Class HelloWorldRunner. Use to test your code is working in a very basic scenario.

Constructor
----------------------

======================== ===========================================================================================
**HelloWorldRunner()**   Initializes a new instance of the `HelloWorldRunner Class <#helloworldrunner-class>`_.
======================== ===========================================================================================

**Code Examples**

.. code-block:: csharp
   :caption: C#
   :name: csharp_HelloWorldRunner_ctr

   HelloWorldRunner mythingy = new HelloWorldRunner();

.. code-block:: vbnet
   :caption: VB.Net
   :name: vbnet_HelloWorldRunner_ctr

   HelloWorldRunner mythingy = new HelloWorldRunner()
 

----------

Methods
----------------------

GetMessage
^^^^^^^^^^^^^^^^^^^^^^^^^^^
================================= =======================================================
*String* **GetMessage()**         Gets the 'Hello, World message'.
================================= =======================================================




**Code Examples**

.. code-block:: csharp
   :caption: C#
   :name: csharp_HelloWorldRunner_GetMessage

   var mythingy = new HelloWorldRunner();
   Console.WriteLine(mythingy.GetMessage());

.. code-block:: vbnet
   :caption: VB.Net
   :name: vbnet_HelloWorldRunner_GetMessage

   dim mythingy = new HelloWorldRunner()
   Console.WriteLine("Output: " + mythingy.GetMessage())
 
----------

HelloWorldProgram Class
==========================
- Namespace: HelloWorld

A program class.

----------

Methods
----------------------

Main
^^^^^^^^^^^^^^^^^^^^^^^^^^^
================================= =======================================================
*void* **Main(String[] args)**    Mains the specified arguments. Dirk customization.
================================= =======================================================
Arguments:                        *System.String[]*  **Args**  The arguments.
================================= =======================================================
 




