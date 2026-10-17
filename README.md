# Oximeter PI Logger

Logs perfusion index (PI), SpO2 and pulse from Wellue/Viatom oximeters (O2Ring, SleepU, KidsO2, O2 Max…) over Bluetooth, in the browser.

Open https://iceryan354.github.io/ring-pi-logger/ in **Bluefy** on iPhone (Safari has no Web Bluetooth), or in Chrome/Edge on a computer.

Readings stay on the device (IndexedDB) and export as CSV. Protocol details from [ecostech/viatom-ble](https://github.com/ecostech/viatom-ble) and [home-health-hub/viatom-o2ring-ble](https://github.com/home-health-hub/viatom-o2ring-ble). Uses the real-time 0x1B request (PI + pulse wave), falling back to the legacy 0x17 request.
