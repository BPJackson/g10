#CSS Notes:

###Intermediate CSS and HTML:

1. Normalize VS Reset
  a. Normalize: render all elements consistently/in line with modern standards
      https://necolas.github.io/normalize.css/
  b. Reset: remove ALL styling! only distinctions between inline/block elements
      http://meyerweb.com/eric/tools/css/reset/

2. Positioning
  a. Static: default,
  b. Relative: relative when you want use absolute
  c. Absolute: when you postion something relative to another, stretched:top, left, right, bottom
  d. Fixed: stuck where it is  

3. Selectors
  a. Standard:
    tagname, .class, #id, several selectors, children
    * universal
    + next sibling
    ~ all siblings
    > All direct children

  b. attribute:
    tag(attribute='value')
    tag(attribute^='starts with value')
    tag(attribute$='ends with value')
    tag(attribute*='contains value')

  c. Pseudo:
    i. link based: :link, :visited, :hover, :active
    ii. intercation based: :focus, ::selection,
    iii. text based: :first-line, :first-letter, :before{content: '...'}, :after{content: '...'}
    iv. child: first-child, nth-of-type etc
    v. other: :not(.other-selector)

4. Tables
  a. Multi Dimensional
      <table>
          <caption>The Title of my table</caption>
          <thead>
              <tr> 'Table row'
                  <th>Header One</th> 'Table Header'
                  <th>Header Two</th>
                  <th>Header Three</th>
              </tr>
          </thead>
          <tbody>
              <tr>
                  <td>Column one data</td> 'Table Data'
                  <td>Column two data</td>
                  <td>Column three data</td>
              </tr>
              <tr>
                  <td>Column one data</td>
                  <td colspan="2">Spans column one AND two</td>
              </tr>
          </tbody>
          <tfoot>
              <tr>
                  <td>Summary of column one</td>
                  <td>Summary of column two</td>
                  <td>Summary of column three</td>
              </tr>
          </tfoot>
      </table>

  b. Description Lists <dl>
    <dl>
      <dt>HTML</dt> 'Description Term'
      <dd>Hypertext Markup Language</dd> 'Description Definition'
      <dt>CSS</dt>
      <dd>Cascading Style Sheets</dd>
      <dt>JS</dt>
      <dd>JavaScript</dd>
    </dl>

    border: width style color
    solid | dotted | dashed | double | groove | ridge | inset | outset | none | hidden
    border-radius: top-left top-right bottom-right bottom-left
    Can do height / width for elliptical shape
    box-shadow: h-offset v-offset radius spread color
    box-sizing: content-box | padding-box | border-box (what do h/w refer to)
    overflow: visible | scroll | auto | hidden
    min-height max-height

5. Lists:
    list-style-type: disc | circle | square | none | decimal | decimal-leading-zero | upper-alpha | upper-roman | lower-alpha | lower-roman
    list-style-position: inside | outside
    list-style-image: url(...)
    
6. Colors
  a. Hexadecimal / Hex #FFBBCC
      Short for hexadecimal, a base 16 number system
      In hexadecimal each byte is represented by characters 0-9 and A-F (A=10,F = 16)

  b.RGB & RGBA rgb(255, 0, 0),rgba(255, 0, 0, 0.5)
    Color values can be between an integer between 0 and 255
    Color values can also be a float percentage between 0 and 100, ex: 50.15%
    The last argument in rgba is for alpha, think transparency

  c.HSL & HSLA: hsl(360, 100%, 50%), hsla(360,100%,50%,0.5)
    first number is color hues: 0/360 = red, 120 = green, 240 = blue
    second number is a percentage of saturation
    third number is a percentage of brightness
    If using HSLA the last number is Alpha (transparency) values 0-1


flexbox
media queries
transitions
transforms
animations
