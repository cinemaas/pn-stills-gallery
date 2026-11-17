# Paranormal Nobodies contact sheet

Phone-friendly numbered library with likes, checkmarks, current AE shot thumbnails, slot assignments and a Done review.

G/P: stylized stills. E: existing AE assets. S: timeline slots. Public share links contain selections only. The authenticated local AE bridge and private connection key are never published here.

Done applies supported still swaps when privately connected to the Mac; baked clip assignments are saved for a scene rebuild.

After a successful still swap, the bridge renders the changed slot from the saved AE master, publishes its thumbnail and assigned image number, and updates `current_opening.json`. Open galleries check for updates every 15 seconds. A failed AE swap does not update the preview. The public read-only preview endpoint contains no connection credentials.
