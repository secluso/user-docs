# Pairing with Your Camera

This is the final step. Your phone forms a direct, encrypted connection to the
camera, hands it your Wi-Fi details, and exchanges keys.

The app guides you through pairing in four numbered steps.
 
## Step 1: Scan the camera QR code

Press **Add your first camera** in the **System** tab or **ADD CAMERA** in the **Home** tab. The app will then ask you to scan the camera QR code.

<div class="shot-row" markdown>

<figure markdown>
![System tab having an option for adding a camera](img/relay-connected.webp){ .phone }
<figcaption>1. Tap <strong>Add your first camera</strong> in the <strong>System</strong> tab to start adding your Secluso camera.</figcaption>
</figure>

<figure markdown>
![Home tab showing and option for adding a camera](img/add-camera-home.webp){ .phone }
<figcaption>2. Tap <strong>ADD CAMERA</strong> in the <strong>Home</strong> tab to start adding your Secluso camera.</figcaption>
</figure>

</div>

## Step 2: Connect to the camera

The app discovers your camera over a temporary, direct link. You'll see two
quick system prompts. Approve both.

<div class="shot-row" markdown>

<figure markdown>
![Permission dialog: allow Secluso to find nearby devices](img/camera-permission-nearby.webp){ .phone }
<figcaption>1. Tap <strong>Allow</strong> so the app can find nearby devices.</figcaption>
</figure>

<figure markdown>
![Searching for the camera device](img/camera-searching.webp){ .phone }
<figcaption>2. The app searches for your camera.</figcaption>
</figure>

<figure markdown>
![Connect to device: temporary Wi-Fi network named Secluso](img/camera-wifi-connect.webp){ .phone }
<figcaption>3. Tap <strong>Connect</strong> to join the camera's temporary <code>Secluso</code> Wi-Fi.</figcaption>
</figure>

</div>

!!! note "Why a temporary Wi-Fi network?"
    The camera briefly broadcasts its own `Secluso` network so your phone can
    reach it directly, before it's on your home Wi-Fi. This is how the secure pairing
    handshake happens.

## Step 3: Enter camera and WiFi details

Enter a name for the camera as well as the information for your home WiFi network that the camera needs to connect to, then tap
**Continue**.

![Camera Setup form: Camera Name, Wi-Fi Network, Wi-Fi Password](img/camera-setup-details.webp){ .phone }

| Field | What to enter |
| --- | --- |
| **Camera Name** | A friendly label, e.g. *Front Door* |
| **Wi-Fi Network** | Your home network name (SSID) |
| **Wi-Fi Password** | Your home network password |

!!! warning "Use your everyday Wi-Fi details"
    Enter the network the camera should join **permanently**: your normal home
    Wi-Fi, not the temporary `Secluso` network from Step 1.

!!! note "Your Wi-Fi password is never stored"
    Credentials are sent directly to the camera over the encrypted link. They
    are never saved on your phone or any server.

## Step 4: Pair and exchange keys

The app sets up encryption with the camera, progressing through three stages.
Approve notifications so you can receive alerts.

<div class="shot-row" markdown>

<figure markdown>
![Pairing progress at 45%: encrypted channel complete, key exchange in progress](img/camera-pairing-progress.webp){ .phone }
<figcaption>Encrypted channel, then key exchange, then camera config.</figcaption>
</figure>

<figure markdown>
![Permission dialog: allow Secluso to send notifications](img/camera-permission-notifications.webp){ .phone }
<figcaption>Tap <strong>Allow</strong> to get motion and person alerts.</figcaption>
</figure>

</div>

## Done: camera paired

When pairing finishes, your camera is **Connected** with **E2EE Active**. Tap
**Go to Home**, or **Add Another Camera** to repeat the process.

![Camera Paired screen: front door, Connected, E2EE Active](img/camera-paired.webp){ .phone }

## Using your camera

<div class="shot-row" markdown>

<figure markdown>
![Home screen showing relay connected, one camera, front door live tile](img/home-with-camera.webp){ .phone }
<figcaption>The <strong>Home</strong> tab lists your cameras and recent activity.</figcaption>
</figure>

<figure markdown>
![Front door camera screen with Tap to view live and saved clips](img/camera-live-view.webp){ .phone }
<figcaption>Tap a camera to view live, see activity, and find saved clips.</figcaption>
</figure>

</div>

Open the **Settings** tab to choose your push delivery method and toggle
**Person**, **Motion**, and **System** alerts independently.

![Settings screen: Dark Mode, Push Notifications, Person/Motion/System alerts](img/settings.webp){ .phone }

!!! note "Not receiving alerts?"
    Make sure **Push Notifications** is on in Settings, that you tapped
    **Allow** on the notification prompt during pairing, and that a push
    delivery method is selected.
