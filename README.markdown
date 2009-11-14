# Weight Converter - Converts a number from one weight to another

**Author**: [George Ornbo][]
**Source**: [Github][]

## Compatibility

* ExpressionEngine Version 1.6.x
* PHP 5.x

## License

Weight Converter is free for personal and commercial use. 

If you use it commercially a donation of $10 is suggested. You can send [donations here](http://pledgie.com/campaigns/6994). 

Weight Converter is licensed under a [Open Source Initiative - BSD License][] license.

## Installation

This file pi.weight_converter.php must be placed in the /system/plugins/ folder in your [ExpressionEngine][] installation.

## Name

Weight Converter

## Synopsis

Converts a number from one weight to another

## Description

The plugin converts a number from one weight to another. It is possible to specify the number of decimals, the decimal separator and the thousands separator.

    {exp:weight_converter from="kg" to="lb"}1.345{/exp:weight_converter}
	
## Parameters

    from
    
* lb - Pounds
* g - Grams
* kg - Kilograms
* oz - Ounzes
* st - Stones
* short_ton - Short Ton (UK)
* long_ton - Long Ton (US)

The Unit to convert from. Use syntax as above eg for stone use "st":

    to

* lb - Pounds
* g - Grams
* kg - Kilograms
* oz - Ounzes
* st - Stones
* short_ton - Short Ton (UK)
* long_ton - Long Ton (US)

The Unit to convert to. Use syntax as above eg for stone use "st":

    decimals
  
The number of decimal places to show. Default: 2.

    dec_point
  
The character to use for the decimal point. Default: .

    thousands_sep
  
The character to use for thousands separator. Default: SPACE


## Examples

Convert from kg to lbs

    {exp:weight_converter from="kg" to="lb"}2.1234{/exp:weight_converter}
    
Convert from g to st with one decimal place

    {exp:weight_converter from="kg" to="lb" decimals="1"}2.1234{/exp:weight_converter}

[George Ornbo]: http://shapeshed.com/
[Github]: http://github.com/shapeshed/weight_converter.ee_addon
[ExpressionEngine]:http://www.expressionengine.com/index.php?affiliate=shapeshed
[Open Source Initiative - BSD License]: http://opensource.org/licenses/bsd-license.php