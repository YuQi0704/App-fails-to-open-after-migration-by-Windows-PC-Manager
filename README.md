# App-fails-to-open-after-migration-by-Windows-PC-Manager
After using Windows PC Manager's software migration to move an app, it fails to launch. Broken NTFS junctions remain in the original `AppData` folder. The target path lacks write permissions, causing partial migration failure. These invalid junctions point to missing paths and block startup, even after reinstallation.
