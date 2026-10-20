ZUTSHOE 3D AR TRY-ON - DEPLOY NOTES

Files:
- index.html: complete storefront with AR try-on prototype
- sample-sneaker.glb: sample 3D shoe model required by the try-on feature

Deployment:
1. Upload BOTH files into the same public folder on your website.
2. Ensure the GLB file URL works, e.g. https://your-domain/sample-sneaker.glb
3. Deploy on HTTPS (Vercel normally provides HTTPS).
4. Test in a current Chrome browser on Android or Safari on iPhone.
5. Grant camera permission and ensure the device has internet access to download Three.js and MediaPipe tracking modules/models.

Troubleshooting:
- If the status mentions Three.js / GLB loader / MediaPipe could not be downloaded, the browser/network is blocking the required CDN. Try another network and disable content blockers.
- If it says sample-sneaker.glb failed to load, upload that file beside index.html and check the URL is publicly accessible.
- Camera requires HTTPS and permission.

This is a browser-based visual try-on prototype, not a certified shoe-size fitting tool. One-camera pose landmarks can be approximate.
