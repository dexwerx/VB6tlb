/* Copyright © 2017 Dexter Freivald. All Rights Reserved. DEXWERX.COM
*
* VB6.idl
*
* VBWERX Core Language Extensions
*	- 64Bit LongLong type as an alias to Currency, CLngLng()
*	- LongPtr type as an alias to Long
*	- .NET style Interfaces ISubclass, IEnumerator, IDisposable, ICallback (Early Binding only)
*	- Standardized Mem Alloc and Free (CoTaskMemAlloc/CoTaskMemFree)
*	- Standardized Subclassing Interface and related APIs
*	- Typed (and untyped) Memory Access adapted from Michel Rutten's VBVM6Lib
*	- AryPtr() for access to an Array's SAFEARRAY struct
*	- Access to variable pointers via Ref and RefAry (VarPtr/VarPtrArray)
*	- Read/Write Reference Pointers to VB's Reference Types via StrRef()/AryRef()/ObjRef()
*	- ObjSet() calls AddRef when setting an Objects Ptr
*
*	- COM / OLE Interfaces IStream
*	- IID/CLSID/UUID type
*	- Multithreading APIs, threadsafe PostMessage
*	- .NET style Sized System Types Int16/Int32/Int64/IntPtr
*	- NOTE: A Typelib'd SAFEARRAY(void)* sidesteps VBs Unicode/ANSI Conversion in MIDL
*	- TODO: Add User Control Interfaces? or keep in OLE
**/

This typelib is built using MIDL, and requires a Windows SDK environment to build.
