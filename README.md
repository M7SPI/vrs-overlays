## Overlays and controls for Virtual Radar Server using Leaflet maps

This JavaScript code is a plugin for the ADSB aircraft tracking [Virtual Radar Server](http://www.virtualradarserver.co.uk) software. The Javascript files need to be used with the Virtual Radar Server [Custom Content plugin](http://www.virtualradarserver.co.uk/Documentation/CustomContent/Default.aspx).

Note that this is the first code that I have written and published on GitHub. I'm not a professional programmer, rather was interested to try and put something together for personal use but realised that there is some demand from the wider community for this. I'm sure there's better or more efficient ways of writing the code, and further improvements that can be made to include additional features. Therefore I welcome constructive feedback and pull requests to improve and/or add further features.

My Virtual Radar server page is at [virtualradaruk.com](http://www.virtualradaruk.com).

### IMPORTANT NOTICE: These overlays contain aviation airscape, weather, navigational aids, airfield information, etc. All of these are purely for entertainment / hobby use and MUST NEVER be relied upon to any extent for real world aviation / flying. You should always use the latest legal airspace charts and weather information as published by official sources. This is not an official source. By using this code you agree to make users of your webpage aware of this, and agree that the publisher is not responsible for any loss or damage resulting from the use of this code. The airspace charts, navigational aids,aerodrome information, weather, etc will not be 100% complete or accurate and will contain errors.

### THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

I am grateful for the following resources which have been used in this code:

- Airspace overlay data courtesy of [Open AIP](http://www.openaip.net)
- Weather overlay images courtesy of [Aeris weather](https://www.aerisweather.com)
- Waypoint markers from [sam210723](https://github.com/sam210723/vrs-waypoints)
- Leaflet grouped layer control from [ismyrnow](https://github.com/ismyrnow/leaflet-groupedlayercontrol)
- Night and day overlay from (Jörg Dietrich)(http://joergdietrich.github.io/Leaflet.Terminator/)
- Leaflet colour markers from (pointhi)[https://github.com/pointhi/leaflet-color-markers]

For the weather overlays to work you will need to sign up for an API code from [Aeris Weather](https://www.aerisweather.com/signup/developer/).
