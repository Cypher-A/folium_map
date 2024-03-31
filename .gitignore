# %%

import folium

m = folium.Map(location=[28.5275544,77.0441712], zoom_start=10)

folium.CircleMarker(location=[28.5275544,77.0441712], radius=15, popup="Galgotias University").add_to(m)

folium.Marker(location=[28.5275544,77.0441712], popup="Galgotias University").add_to(m)

folium.TileLayer('openstreetmap', name='StreetMap', attr='StreetMap').add_to(m)

folium.TileLayer('stamentoner', attr='Stamentoner').add_to(m)

folium.LayerControl().add_to(m)

m.save('project_map.html')
