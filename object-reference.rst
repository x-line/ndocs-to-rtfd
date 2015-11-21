=======================
Object Reference
=======================

The ``HelloWorld`` namespace is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. 

- Assembly: HelloWorld.dll version 4.0125
- Download: http://ironsoftware.com/downloads/packages/helloworld.latest.zip
- Nuget: ``PM> install HelloWorld``


*******
Classes
*******

HelloWorldRunner Class
======================

- Namespace: HelloWorld

Class HelloWorldRunner. Use to test your code is working in a very basic scenario.

Constructor
----------------------

======================== ===========================================================================================
``HelloWorldRunner()``   Initializes a new instance of the `HelloWorldRunner <HelloWorldRunner Class>`_ class.
======================== ===========================================================================================

**Code Examples**

.. code-block:: csharp
   :linenothreshold: 10
   :caption: C#

   HelloWorldRunner mythingy = new HelloWorldRunner();

.. code-block:: vbnet
   :linenothreshold: 10
   :caption: VB.Net

   HelloWorldRunner mythingy = new HelloWorldRunner()
 

Methods
----------------------
================================= ========================================
String ``GetMessage()``           Gets the 'Hello, World message'.
================================= ========================================


**Code Examples**

.. code-block:: csharp
   :linenothreshold: 10
   :caption: C#

   var mythingy = new HelloWorldRunner();
   Console.WriteLine(mythingy.GetMessage());

.. code-block:: vbnet
   :linenothreshold: 10
   :caption: VB.Net

   dim mythingy = new HelloWorldRunner()
   Console.WriteLine("Output: " + mythingy.GetMessage())
 

HelloWorldProgram Class
==========================
- Namespace: HelloWorld

Class Program.

Methods
----------------------

================================= =======================================================
void ``Main(String[] args)``      Mains the specified arguments. Dirk customization.
================================= =======================================================
 

**Arguments**

- **Args** ``System.String[]`` The arguments.
