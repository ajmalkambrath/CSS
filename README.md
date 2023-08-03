# CSS

### Display properties

```
Inline: 
>> Allow another element to sit to their left and right no top bottom margin
>> can’t have width and height

block element
>> Block level element occupies entire space of its parent element, force a line break after the block element

inline-block
>> Allow other element to sit to their left & right respect to top & bottom, respect to the Hight and width

```
### Position

```
Relative: 
>> Position relative to its origin (parent) move  without to its parent

Absolute
>> disrupt the environment
>> Position referance to its parent if not parent then root

Fixed
>> Position relative to origin (window)

Static
>> Default
```

### Box Model

By defualt box-sizing:content-box
```
Margin: 
>> Space between border and neighour element
Padding
>> space between border and elemement

Border
>> 

```

### Align div center

```

```

### Specificity

```
>> #ID selectors have a higher specificity than attribute selectors
>> !important overrides any other declarations 
>> more specific will take priority
>> last style will take priority
```

<div class="relative">
  <div class="h-2 bg-gradient-to-r from-green-400 via-yellow-400 to-red-400"></div>
  <div class="absolute -top-1 left-[20%] w-max flex flex-col justify-center items-center text-center">
     <div class="h-[20px] w-[10px] cursor-pointer rounded-full bg-green-500 shadow-lg"></div>
    <div class="mt-1">
      <label class="text-sm font-semibold">Low</label>
    </div>
  </div>
</div>

const riskLevels = [
    { level: 1, color: 'from-green-400', text: 'Low' },
    { level: 2, color: 'via-yellow-400', text: 'Medium' },
    { level: 3, color: 'to-red-400', text: 'Strong' },
    { level: 4, color: 'to-red-400', text: 'Danger' },
  ];

  const riskData = riskLevels.find((data) => data.level === currentRiskLevel);

  

