---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: |
        Eindhoven Center for the Philosophy of Artificial Intelligence
      text:         <p style="font-size:1.25em">The Eindhoven Center for the Philosophy of Artificial Intelligence (ECPAI) advances the understanding of philosophical issues in AI and investigates the ethical and social implications of AI technology through philosophical reflection. Its members, mostly comprised of researchers in the  <a href="https://www.tue.nl/en/research/research-groups/innovation-sciences/philosophy-ethics/" target="_blank">Philosophy & Ethics Group</a> at <a href="https://www.tue.nl/en/" target="_blank">Eindhoven University of Technology</a>, contribute to interdisciplinary AI research and engage with industry, policy, and civil society actors to ensure the responsible development and use of AI.</p>
    design: 
      columns: '2'
    
# test cluster pic

<script src="https://code.highcharts.com/highcharts.js"></script>
<script src="https://code.highcharts.com/modules/networkgraph.js"></script>

<div id="container"></div>

#container {
  min-width: 320px;
  max-width: 500px;
  margin: 0 auto;
  height: 500px;
}

# - block: slider
  #  content:
   #   slides:
    #  - title: '[Trustworthy AI](/project/trustworthy-ai/)'
     #   content: '🤝 AI we can trust'
      #  align: right
       # background:
        #  image:
         #   filename: project-trustworthy-ai.png
          #  size: cover
           # filters:
            #  brightness: 0.5
         # position: center
         # color: '#666'
     # - title: '[Value Alignment](/project/value-alignment/)'
      #  content: '⚖️ Ethical AI'
       # align: center
       # background:
        #  image:
         #   filename: project-value-alignment.jpg
          #  size: cover
           # filters:
            #  brightness: 0.5
         # position: center
         # color: '#666'
      # - title: '[AI in Education](project/ai-education/)'
       # content: '🎓Teaching with AI'
       # align: left
       # background:
        #  image:
         #   filename: project-ai-education-wide.jpg
          #  size: cover
           # filters:
            #  brightness: 0.7
          # position: center
          # color: '#666'
       # link:
        #  icon: envelope
        #  icon_pack: fas
        #  text: Contact Us
        #  url: /#contact
  #  design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
     # slide_height: '512px'
     # is_fullscreen: false
      # Automatically transition through slides?
     # loop: true
      # Duration of transition between slides (in ms)
     # interval: 3000

  - block: portfolio
    id: events
    content:
      title: Events and News
      filters:
        folders:
          - post
          - event
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Events
          tag: event
        - name: News
          tag: news
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

#  - block: collection
#    id: posts
#    content:
#      title: Latest News
#      subtitle: ''
#      text: ''
#     # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view (list, compact, card, citation, showcase, masonry)
#      view: compact
#      columns: '2'

#  - block: collection
#    content:
#      title: Upcoming and Recent Events
#     # text: |-
#      #  {{% callout note %}}
#      #  Quickly discover relevant content by [filtering publications](./publication/).
#      #  {{% /callout %}}
#      count: 3
#      filters:
#        folders:
#          - event
#        exclude_featured: false
#    design:
#      columns: '2'
#      view: compact

  - block: collection
    content:
      title: Publications
     # text: |-
      #  {{% callout note %}}
      #  Quickly discover relevant content by [filtering publications](./publication/).
      #  {{% /callout %}}
      count: 5
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      # Choose a layout view (list, compact, card, citation, showcase, masonry)
      view: citation

  - block: markdown
    content:
      title: Partners
      subtitle: ''
      text: |
        <div class="container">
          <div class="row align-items-start">
            <div class="col">
              <!-- Intentionally left blank? If not, add content here -->
            </div>
            <div class="col text-center">
              <a href="https://www.tue.nl/en/research/institutes/eindhoven-artificial-intelligence-systems-institute/" target="_blank">
                <img alt="EAISI logo" src="https://raw.githubusercontent.com/ephil-ai/ephil.ai/main/assets/media/EAISI-logo.jpg" height="200">
              </a>
            </div>
            <div class="col text-center">
              <a href="https://www.tue.nl/en/research/research-areas/humans-and-technology/" target="_blank">
                <img alt="CHT logo" src="https://raw.githubusercontent.com/ephil-ai/ephil.ai/main/assets/media/CHT-logo.jpg" height="200">
              </a>
            </div>
            <div class="col">
              <!-- Intentionally left blank? If not, add content here -->
            </div>
          </div>
        </div>
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        
      # Contact (add or remove contact options as necessary)
      #email: test@example.org
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      #address:
      #  street: 450 Serra Mall
      #  city: Stanford
      #  region: CA
      #  postcode: '94305'
      #  country: United States
      #  country_code: US
     #   directions: '**Eindhoven Center for the Philosophy of AI** <br>
 # Atlas 9.328 <br>
 # PO Box 513 <br>
 # 5600 MB Eindhoven <br>
 # The Netherlands'
     # office_hours:
      #  - 'Monday 10:00 to 13:00'
       # - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
     # coordinates:
      #  latitude: '37.4275'
      #  longitude: '-122.1697'  
      contact_links:
        - icon: envelope
          icon_pack: fas
          name: Email us
          link: 'info@ephil.ai'
        - icon: twitter
          icon_pack: fas
          name: Follow us on LinkedIn
          link: 'https://www.linkedin.com/company/ecpai'
       # - icon: video
       #   icon_pack: fas
       #   name: Zoom Me
       #   link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
     # form:
      #  provider: netlify
      #  formspree:
      #    id:
       # netlify:
          # Enable CAPTCHA challenge to reduce spam?
       #   captcha: false
    design:
      columns: '2'
---
