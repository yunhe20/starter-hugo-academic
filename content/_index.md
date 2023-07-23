---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    id: news
    content:
      title: News
      text: |2-
        - [2023-06] I am awared as the outstanding graduate student of Shanghai (Top 3%)!
        - [2023-02] First-authored paper [Grad-PU](https://arxiv.org/abs/2304.11846) is accepted by CVPR 2023.
        - [2022-02] First-authored paper [D-PCC](https://arxiv.org/abs/2204.12684) is accepted by CVPR 2022.
    design:
      columns: '1'
  # - block: collection
  #   id: publications
  #   content:
  #     title: Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: compact
  - block: portfolio
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      # buttons:
      #   - name: All
      #     tag: '*'
      #   - name: Deep Learning
      #     tag: Deep Learning
      #   - name: Other
      #     tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Machine Learning Engineer (Full-Time)
          company: MeiTuan
          company_url: 'https://www.meituan.com/en-US/about-us'
          company_logo: meituan
          location: Shanghai, China
          date_start: '2023-07-12'
          date_end: ''
          description: Apply advanced meachine learning techniques for ads ranking and creatives selection in Meituan app.
        - title: Machine Learning Engineer (Intern)
          company: ByteDance
          company_url: 'https://www.bytedance.com/en/'
          company_logo: douyin
          location: Shanghai, China
          date_start: '2022-05-01'
          date_end: '2022-08-15'
          description: Apply machine learning methods to improve the video recommendation system of Douyin (Chinese TikTok) app.
    design:
      columns: '2'
  - block: accomplishments
    id: honors
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Honors and Awards'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_end: ''
          date_start: '2023-06-15'
          description: ''
          organization: Shanghai Municipal Education Commission
          organization_url: http://study.edu.sh.gov.cn/en/
          title: 'Outstanding Graduate Student of Shanghai (Top 3%)'
        - date_end: ''
          date_start: '2023-05-20'
          description: ''
          organization: Fudan University
          organization_url: https://www.fudan.edu.cn/en/
          title: 'Outstanding Graduation Thesis of Fudan University (Top 10%)'
        - date_end: ''
          date_start: '2022-01-16'
          description: ''
          organization: Fudan University
          organization_url: https://www.fudan.edu.cn/en/
          title: 'Outstanding Teaching Assistant of Fudan University (Top 10%)'
        # - date_end: ''
        #   date_start: '2022-12-10'
        #   description: ''
        #   organization: Fudan University
        #   organization_url: https://www.fudan.edu.cn/en/
        #   title: 'First-class Award for Outstanding Student at Fudan University (Top 20%)'
        # - date_end: ''
        #   date_start: '2020-06-30'
        #   description: ''
        #   organization: Chongqing University
        #   organization_url: http://english.cqu.edu.cn/
        #   title: 'Outstanding Graduate of Chongqing University (Top 10%)'
    design:
      columns: '2'
  - block: accomplishments
    id: teaching
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Teaching Assistant'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_end: '2021-01-25'
          date_start: '2020-09-10'
          description: ''
          organization: Fudan University
          organization_url: https://www.fudan.edu.cn/en/
          title: 'Data Structure (COMP130184.01)'
        - date_end: '2022-01-30'
          date_start: '2021-09-05'
          description: ''
          organization: Fudan University
          organization_url: https://www.fudan.edu.cn/en/
          title: 'Python Programming (COMP110042.13)'
    design:
      columns: '2'

---
