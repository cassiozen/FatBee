# Fat Bee 🐝

<p align="center" width="100%">
<img src="./fatbee.png" width="940" />
</p>

### FatBee is a low-profile mechanical keyboard that mixes a familiar layout with scientifically-proven ergonomic principles.


## What?

The keyboard design we use today is a relic from the 1800s, created to overcome mechanical limitations, not for comfort. This can lead to wrist pain and other injuries with prolonged use.

While ergonomic keyboards exist, they can be intimidating for new users. But here's the thing: Studies show that even slight key splitting, tenting, and a lower back angle can significantly reduce discomfort and potential injuries.

FatBee does precisely that: A little bit of everything, just enough to get more comfort while keeping a familiar look and feel, designed to be **approachable by users with varying typing techniques (or no typing technique at all.)**

## What's in this repo?

- 3D-print case & palmrest source.
- PCB source (KiCad)
- keyboard layout (standard keyboard-layout-editor.com JSON)

### Coming soon

- ZMK profile (working on it)


## FatBee's Characteristics

- Gently split layout for a natural typing position<br>
  **Why it matters:** The posture where the wrist bends outward towards the little finger (called Ulnar Deviation) is a common cause of repetitive strain injuries.

- Moderate tenting to avoid forearm pronation<br>
  **Why it matters:** When the palms of your hands face down, the bones in the forearms squeeze the carpal tunnel, potentially causing nerve and tendon issues.

- Integrated palm rest and low back angle for improved wrist posture:<br>
  **Why it matters:** When wrists are bent upwards (called wrist extension), it can restrict blood circulation, leading to pain, fatigue, and numbness. A palm rest shouldn't be an accessory but an integral keyboard part.

- Centralized alphanumerics for intuitive positioning<br>
  **Why it matters:** Proper keyboard alignment with your body reduces unnecessary reaching and twisting, which can contribute to shoulder and upper back strain.

## One thing led to another...

Splitting the keys at an angle while keeping them familiar-looking required a few tricks:

- Centralizing the alphas
- Adding the signature "fat" B key
- A shorter stagger between the rows R2-R3

While these met the goal of familiarity, what makes this layout remarkable is that these exact constraints directly led to some very unique features.
For one, it looks cool! But for a more concrete example, after centralizing the alphas, I was left with some unusual empty space on the left, which led to an additional key column. Think of it as a mini macro pad. It has:

- An escape key directly aligned with the numeric row<br>
  I love compact layouts. Still, as a software engineer, I heavily use "Esc, "~", and" ', so it's nice to have them all readily accessible and not in a separate layer.
- The function key, followed by three buttons that pair with it, creates a convenient "control center"<br>
  Volume control (Tap to increase, Fn+tap to decrease), Brightness (same principle), and App cycling (Mimics CMD+Tab and CMD+Shift+Tab).

## Prior art

- Apple keyboards - I know this sounds weird, given that Apple doesn't make ergonomic keyboards nowadays, but what they have been doing since the 90s is slowly reducing the stagger between rows R2 and R3. Could it be just for aesthetics? Sure, still, it does pave the way...
- Jones keyboard layout ([GitHub](https://github.com/jpskenn/Jones)) - Combines centralized alphanumerics with non-staggered rows R2-R3.
- Logitech Wave keys ([Logitech.com](https://www.logitech.com/en-us/products/keyboards/wave-keys.html)) - Despite feeling mushy and cheap, it does deliver great ergonomic improvements while still looking familiar.

## License

<a href="https://creativecommons.org/licenses/by-nc/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC 4.0</a>, meaning you can use it, remix, adapt, but not sell as a product (If you want to sell a kit or finished product, get in touch at cassiozen (at) gmail com.)

<img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/png/by-nc.png" height="30">
