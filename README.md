# Voron Support Ticket Guideline

Do you have an issue and don't know how to fix it? No worries, we are here to help you out!
But to assist you properly, we need to understand the situation. 

TL:DR; Be detailed, be most excellent to each other, check your grammar and formatting.

I recommend that you write your ticket beforehand in a text editor of your choice. Then you can post it all in one piece when you are ready. Discord only allows up to 2000 characters per message. Nitro users can post up to 4000 characters. You might want to divide your text into sections you can then post later within a couple of messages. I end every section with a dashed line `- - - - - - - - - - - - - - - - - - - -` as a hint so that I know what to copy out of my editor into discord later. See **[EXAMPLE.md](EXAMPLE.md)**


## Summary

Begin with a summary of your situation. Answer the following questions:

- What does not work? 
- What are your expectations?
- What have you tried to address the problem? Share your analysis results with us

Add photos and maybe even videos when possible. Try to structure and format your text. 

### Formatting

You can use Discords limited formatting tools `**bold**`, `_italic_` to make your text more readable. I use bold text as section headers.

You can use single ticks `` `code` `` to format text as code inline. `code`   
You can use triple ticks `` ``` code ... ``` `` to format text over multiple lines as code

```
[heater_fan hotend_fan]
pin: FAN1
fan_speed: 1
heater: extruder
heater_temp: 40.0
```


## Details

After that, give us all the details. It's usually better to list too many details than too few. Here are a couple of things which _could_ be important. 

- what version of the printer are you running
- what mods/extruder do you use
- slicer and klipper version
- what material was printed (brand/filament)
- attach your gcode / 3mf files
- slicer settings
- list your hardware (hotend, fans, pcb, mcu, ..)
- post your klipper config
- ...


### Example
If you have an issue with your toolhead not extruding filament then mention: motor, hotend, nozzle, fans, material + temperature, extruder, maybe show pictures of your spool setup and filament path