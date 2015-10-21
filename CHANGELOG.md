ChangeLog
---------

### v1.3.2

- Handle edge case where OS X drives contain a description within parenthesis in `diskutil list`.

### v1.3.1

- Surround Windows script path in double quotes to avoid issues with paths incuding white space.

### v1.3.0

- Add `mountpoint` attribute to drives.

### v1.2.2

- Fix issue where a removable drive was detected as a system drive in Linux.

### v1.2.1

- Fix win32 issue where DeviceID gets part of the device description.

### v1.2.0

- Implement isSystem predicate.

### v1.1.2

- Prevent empty lsblk model crash the module. Return `undefined` description instead.

### v1.1.1

- Prevent empty wmic size crash the module. Return `undefined` size instead.

### v1.1.0

- Return non supported OS error to the callback instead of just throwing it.