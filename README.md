# Cholera Contagion in Europe

Interactive research dashboard for the CUP Economic History of Cholera
project. It visualizes annual population, historical cholera outbreaks, and
daily outbreak timing across Europe.

The application is a static research visualization. Its browser assets are
compiled from the project's canonical Parquet outputs before deployment.

## Publish on GitHub Pages

Upload all files in this folder (including .nojekyll) to the root of a dedicated
public repository. In Settings > Pages, select Deploy from a branch, main,
and / (root). Open the published HTTPS URL after the deployment completes.
No Python, Node.js, build action, or server is required on the hosting service.

## Embed in Google Sites

In Google Sites choose Insert > Embed > By URL and paste the published Pages
URL, including its repository path and trailing slash. Use a full-page embed
or a frame at least 800 pixels tall for the map and animation controls.
Publish the Google Site. A direct link to the dashboard is useful on small screens.

For subsequent data updates replace this repository's deployment files with the
newly generated package; the Google Sites embed URL stays unchanged.
All served data are public and downloadable. Keep raw research inputs elsewhere.
