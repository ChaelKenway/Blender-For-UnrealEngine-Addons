# Unreal Engine Assets Exporter - Release Log
Release Logs: https://github.com/xavier150/Blender-For-UnrealEngine-Addons/wiki/Release-Logs

### Version 4.4.5
- New: New automatic fix for "Armature Child with Bone Parent" potential issue.
    When this issue is detected, you can now automatically fix it by converting the bone parent to an armature modifier.
- New: New automatic fix for "Armature Multiple Root Bones" potential issue.
    When this issue is detected, you can now automatically fix it by adding a new root bone and reparenting the existing root bones to it.
- Fixed: Light Map UVs operator was not registered properly, causing errors when trying to use it.