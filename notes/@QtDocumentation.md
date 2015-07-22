# Tidbits culled from Digia's Qt documentation

---

## Basic QML language types

 + bool            Binary true/false value
 + double          Number with a decimal point, stored in double precision
 + enumeration     Named enumeration value
 + int             Whole number, e.g. 0, 10, or -20
 + list            List of QML objects
 + real            Number with a decimal point
 + string          Free form text string
 + url             Resource locator
 + var             Generic property type

## Basic QML module types

 + color           ARGB color value. The type refers to an ARGB color value. It can be specified in a number of ways:
 + date            Date value
 + font            Font value with the properties of QFont. The type refers to a font value with the properties of QFont
 + matrix4x4       A matrix4x4 type is a 4-row and 4-column matrix
 + point           Value with x and y attributes
 + quaternion      A quaternion type has scalar, x, y, and z attributes
 + rect            Value with x, y, width and height attributes
 + size            Value with width and height attributes
 + vector2d        A vector2d type has x and y attributes
 + vector3d        Value with x, y, and z attributes
 + vector4d        A vector4d type has x, y, z and w attributes

---

### anchors group

 + anchors.top : AnchorLine
 + anchors.bottom : AnchorLine
 + anchors.left : AnchorLine
 + anchors.right : AnchorLine
 + anchors.horizontalCenter : AnchorLine
 + anchors.verticalCenter : AnchorLine
 + anchors.baseline : AnchorLine
 + anchors.fill : Item
 + anchors.centerIn : Item
 + anchors.margins : real
 + anchors.topMargin : real
 + anchors.bottomMargin : real
 + anchors.leftMargin : real
 + anchors.rightMargin : real
 + anchors.horizontalCenterOffset : real
 + anchors.verticalCenterOffset : real
 + anchors.baselineOffset : real
 + anchors.alignWhenCentered : bool

### animation types

 + Animation (base type)
 + AnchorAnimation
 + ParallelAnimation
 + ParentAnimation
 + PathAnimation
 + PauseAnimation
 + PropertyAction
 + PropertyAnimation
 + ScriptAction
 + SequentialAnimation