---
sidebarDepth: 2
description: >-
  GFAvatar is a Flutter Avatar Widget that typically represents the user's
  profile image. It comes with different shapes.
---
# GF Avatar

![img](https://ik.imagekit.io/ionicfirebaseapp/docs/tr:dpr-auto,tr:w-auto/Avatars_2x_cM1srTq6w.png)

## Avatar Info

### Circular Avatar  

![img](https://ik.imagekit.io/ionicfirebaseapp/circular-avatars-2x_YEAePfrqD.png)

GFAvatar comes with different shapes , in which one of the default shape is circle. To place the image inside the avatar, image should be given in `backgroundImage` property.

```dart
import 'package:getwidget/getwidget.dart';

GFAvatar(
  backgroundImage:NetworkImage(AvatarUrl);
)
```

### Standard Avatar

![img](https://ik.imagekit.io/ionicfirebaseapp/slightly-rounded-corners-2x_VCB3GCS2h.png)

Standard GFAvatar is a avatar shape which has a slightly rounded corners.

```dart
import 'package:getwidget/getwidget.dart';

GFAvatar(
  backgroundImage:NetworkImage(AvatarUrl);
  shape: GFAvatarShape.standard
)
```

### Square Avatar

![img](https://ik.imagekit.io/ionicfirebaseapp/square-2x_Zs-9r00cm.png)

Square GFAvatar is a avatar shape which represents a square

```dart
import 'package:getwidget/getwidget.dart';

GFAvatar(
  backgroundImage:NetworkImage(AvatarUrl);
  shape: GFAvatarShape.square
)
```

### Custom Properties

|  |  |
| :--- | :--- |
| **child** | type of \[Widget\], which can have text , icon etc |
| **backgroundColor** | GFColor or Color to fill the background of avatar |
| **foregroundColor** | GFColor or Color to change the textColor inside the avatar |
| **radius** | size of the avatar |
| **minRadius** | minimum size of the avatar |
| **maxRadius**  | maximun size of the avatar |
| **size** | size of the avatar i.e `GFSize.large, GFSize.medium, GFSize.small` |
| **shape** | shape of the avatar i.e, `GFAvatarShape.standard, GFAvatarShape.circle, GFAvatarShape.square` |
| **borderRadius** | extra radius to avatar shapes, not applicable to circular avatar |

