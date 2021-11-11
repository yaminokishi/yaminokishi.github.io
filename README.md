site_name: 3d24rd0
theme:
  name: material
  # custom_dir: material

  # 404 page
  static_templates:
    - 404.html

  # Necessary for search to work properly
  include_search_page: false
  search_index_only: true

  language: es
  font:
    text: Roboto
    code: Roboto Mono

  favicon: assets/favicon.png

  icon:
    logo: logo
  
  palette:

    # Light mode
    - media: "(prefers-color-scheme: light)"
      scheme: slate
      primary: indigo
      accent: indigo
      toggle:
        icon: material/lightbulb-outline
        name: Switch to dark mode

    # Dark mode
    - media: "(prefers-color-scheme: dark)"
      scheme: default 
      primary: indigo
      accent: indigo
      toggle:
        icon: material/lightbulb
        name: Switch to light mode