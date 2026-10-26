# 3D Model Credits

The furniture models in `assets/models/` were downloaded from Sketchfab and are
used under the Creative Commons Attribution (CC-BY) license. Each model's folder
also contains the original `license.txt` from Sketchfab.

| Slot          | Model                               | Author            | License        | Source |
|---------------|-------------------------------------|-------------------|----------------|--------|
| table/table1  | Wooden Table                        | FlukierJupiter    | CC Attribution | https://sketchfab.com/3d-models/wooden-table-0dc1c7d6cbab4d74bef7c4f82abf2caf |
| table/table2  | Bar Table                           | CommonSpence      | CC Attribution | https://sketchfab.com/3d-models/bar-table-4517652104744f4981defb6d4d18e481 |
| table/table3  | Victorian Coffee Table              | Jamie McFarlane   | CC Attribution | https://sketchfab.com/3d-models/victorian-coffee-table-ad38ff95b713412080992a48eab50899 |
| chair/chair1  | Victorian chair                     | Abdullah Mohammed | CC Attribution | https://sketchfab.com/3d-models/victorian-chair-6479a1900b614b59b26784c3a7922eb3 |
| chair/chair2  | Office Chair Modern                 | thethieme         | CC Attribution | https://sketchfab.com/3d-models/office-chair-modern-675f34f7304e4d92812a41e9750539aa |
| chair/chair3  | Old Wooden Chair                    | MaX3Dd            | CC Attribution | https://sketchfab.com/3d-models/old-wooden-chair-3f95ffdc194047ada2d9391828a5d234 |
| shelf/shelf1  | Wooden Bookcases with Books         | Matthew Collings  | CC Attribution | https://sketchfab.com/3d-models/wooden-bookcases-with-books-d0618ac16b2a4a87b9b6c7d5e6765626 |
| shelf/shelf2  | Stainless Steel Shelving            | jimbogies         | CC Attribution | https://sketchfab.com/3d-models/stainless-steel-shelving-restaurant-equipment-01addf6c21304a26a9634cbf725230ef |
| shelf/shelf3  | Old Kitchen Shelf                   | Coozy (GameDevNick) | CC Attribution | https://sketchfab.com/3d-models/old-kitchen-shelf-5da9ec510dfe453b8504e5fd206b062c |

> CC Attribution (CC-BY) requires crediting the author. Keep this file (or an
> equivalent credit) in the project when distributing or deploying it.

## Notes

- Each menu item (3 tables, 3 chairs, 3 shelves) uses a distinct model.
- The Lamp / Bed / Sofa / Cabinet categories in the menu are placeholders in the
  markup (they reuse the shelf thumbnail) and have no models wired in `main.js`.
  To enable them, add `scene.gltf` + textures under
  `assets/models/<category>/<itemN>/` and extend the load loop in
  `complete/main.js`.
