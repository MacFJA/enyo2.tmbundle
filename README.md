enyo2.tmbundle
==============

Features
========
Syntax coloration
-----------------

Commands
--------
Search a word in Enyo API [&#x2303;H]

Avalaible snippets
------------------
* __"Enyo Core"__
	* depends [`depends`&#x21E5;]
	* irand [`irand`&#x21E5;]
	* _Function_
		* bind [`bind`&#x21E5;]
		* asyncMethod [`async`&#x21E5;]
		* job [`job`&#x21E5;]
		* job.stop [`jobstop`&#x21E5;]
		* requiresWindow [`requires`&#x21E5;]
		* call [`call`&#x21E5;]
	* _Array/Object_
		* mixin [`mixin`&#x21E5;]  
		* getObject [`object`&#x21E5;]
		* setObject [`object`&#x21E5;]
		* _Clone_
			* clone [`clone`&#x21E5;]
			* cloneArray [`clone`&#x21E5;]
		* filter [`filter`&#x21E5;]
		* foreach [`foreach`&#x21E5;]
		* map [`map`&#x21E5;]
		* indexOf [`indexof`&#x21E5;]
		* remove [`remove`&#x21E5;]
	* _String_
		* cap [`cap`&#x21E5; | &#x2325;&#x21E7;C]
		* uncap [`cap`&#x21E5; | &#x2325;C]
		* macroize [`macro`&#x21E5;]
		* quickMacroize [`qmacro`&#x21E5;]
		* format [`format`&#x21E5;]
	* _Cookie_
		* getCookie [`cookie`&#x21E5;]
		* setCookie [`cookie`&#x21E5;]
		* Remove Cookie [`cookie`&#x21E5;]
	* _Log_
		* log [`log`&#x21E5; | &#x2303;L]
		* warn [`warn`&#x21E5; | &#x2303;L]
		* error [`error`&#x21E5; | &#x2303;L]
	* _Test_
		* isString [`string?`&#x21E5;]
		* isFunction [`func?`&#x21E5;]
* __Kind__
	* Kind [`kind`&#x21E5; | &#x2303;K]
	* Kind - Component [`kComponent`&#x21E5;]  
	Create a kind based on a _enyo.Component_
	* Kind - Control [`kControl`&#x21E5;]  
	Create a kind based on a _enyo.Control_
	* _Properties_
		* Kind - Oop - Statics [`addKindStatics?`&#x21E5;]  
		Add statics properties/functions (snippet use on kind creation)
		* Kind - Object - Published [`addKindPublished`&#x21E5;]  
		Add published properties (snippet use on kind creation)
		* Kind - Component Event [`addKindEvents`&#x21E5;]  
		Add published event (snippet use on Component based kind creation)
		* Kind - Component Handlers [`addKindHandlers`&#x21E5;]  
		Add handled event (snippet use on Component based kind creation)
	* inherited [`inherited`&#x21E5; | &#x2303;&#x2191;]
* __Component__
	* makeId [`id`&#x21E5;]
	* destroy [`destroy`&#x21E5; | &#x2303;&#x232B;]
	* createComponent [`create`&#x21E5;]
	* createComponents [`create`&#x21E5;]
	* getComponents [`getc`&#x21E5;]
	* destroyComponents [`destroy`&#x21E5; | &#x2325;&#x21E7;&#x232B;]
	* addComponent [`addc`&#x21E5;]
	* removeComponent [`removec`&#x21E5;]
	* bubble [`bubble`&#x21E5;]
	* bubbleUp [`bubble`&#x21E5;]
* __Control__
	* _Class_
		* addClass [`class`&#x21E5;]
		* addRemoveClass [`class`&#x21E5;]
		* hasClass [`class`&#x21E5;]
		* getClassAttribute [`class`&#x21E5;]
		* removeClass [`class`&#x21E5;]
	* _Content_
		* getContent [`content`&#x21E5;]
		* addContent [`content`&#x21E5;]
		* setContent [`content`&#x21E5;]
		* Remove Content [`content`&#x21E5;]
	* _Style_
		* addStyles [`style`&#x21E5;]
		* applyStyle [`style`&#x21E5;]
		* Remove Style [`style`&#x21E5;]
	* _Attribute & Node_
		* getAttribute [`attribute`&#x21E5;]
		* setAttribute [`attribute`&#x21E5;]
		* Remove Attribute [`attribute`&#x21E5;]
		* getNodeProperty [`node`&#x21E5;]
		* setNodeProperty [`node`&#x21E5;]
		* hasNode [`node`&#x21E5;]
	* _Bounds_
		* getBounds [`bounds`&#x21E5;]
		* setBounds [`bounds`&#x21E5;]
		* setBounds -Global units [`bounds`&#x21E5;]
	* _Showing & Render_
		* show [`showing`&#x21E5;]
		* hide [`showing`&#x21E5;]
		* showing [`showing`&#x21E5;]
		* render [`render`&#x21E5;]
		* renderInto [`render`&#x21E5;]
		* write [`render`&#x21E5;]
* Inline kind [`{kind`&#x21E5;]
