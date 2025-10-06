---
title: ''
date: 2022-10-24
type: landing
sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      username: admin
  
  - block: experience
    id: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Graduate Research Assistant
          company: Florida International University
          company_url: 'https://www.cis.fiu.edu/'
          company_logo: fiu
          location: FL, USA
          date_start: '2023-05-01'
          date_end: ''
        - title: Graduate Teaching Assistant
          company: Florida International University
          company_url: 'https://www.cis.fiu.edu/'
          company_logo: fiu
          location: FL, USA
          date_start: '2023-01-01'
          date_end: '2023-04-30'   
        - title: Graduate Research Assistant
          company: University of Nevada, Reno
          company_url: 'https://www.unr.edu/cse'
          company_logo:  unr
          location: Nevada, USA
          date_start: '2022-08-01'
          date_end: '2022-12-31'
        - title: Assistant Professor
          company: Daffodil International University
          company_url: 'https://daffodilvarsity.edu.bd/'
          company_logo: diu
          location: Dhaka, Bangladesh
          date_start: '2022-02-01'
          date_end: '2022-07-31'
        - title: Lecturer (Senior Scale)
          company: Daffodil International University
          company_url: 'https://daffodilvarsity.edu.bd/'
          company_logo: diu
          location: Dhaka, Bangladesh
          date_start: '2020-02-01'
          date_end: '2022-01-31'
        - title: Lecturer
          company: Daffodil International University
          company_url: 'https://daffodilvarsity.edu.bd/'
          company_logo: diu
          location: Dhaka, Bangladesh
          date_start: '2016-05-01'
          date_end: '2020-01-31'
        - title: Project Developer (Android)
          company: Walton Group
          company_url: 'https://waltonbd.com/'
          company_logo: walton
          location: Dhaka, Bangladesh
          date_start: '2015-09-01'
          date_end: '2016-03-31'               
    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
        - block: accomplishments
    id: accomplishments
    content:
      title: 'Achievements, Awards, and Services'
      date_format: Jan 2006
      items:
        - date_end: '2025-12-31'
          date_start: '2010-01-01'
          description: |2-
              <span style="font-size: 1.5em;">**Research Awards:**</span>
              * Best Paper Award at the Third International Conference on Smart Systems: Innovations in Computing (SSIC), Springer (2021).

              <span style="font-size: 1.5em;">**Scholarships:**</span>
              * University Scholarship for Outstanding Academic Performance (2010–2014).
              * Undergraduate Entrance Exam Scholarship for achieving the top position (2010–2011).

              <span style="font-size: 1.5em;">**Awards, Fellowships, & Grants:**</span>
              * Publication Grant (Journal) — University Graduate School, Florida International University (2024, 2025).
              * Travel Grant (Conference) — University Graduate School & Knight Foundation School of Computing and Information Sciences (KFSCIS), FIU (2024, 2025).
              * Recognition for Scholarly Publications in Reputed Indexed Journals — Daffodil International University (2020, 2021, 2022).
              * Best Performer-2018 — Dept. of CSE, Daffodil International University (2018).

              <span style="font-size: 1.5em;">**Academic Contributions:**</span><br>
              <span style="font-size: 1.5em;">Committee Member</span>
              * IJCACI 2020 — Organizing Committee, Daffodil International University, Bangladesh; Jahangirnagar University, Bangladesh; South Asian University, India.
              * 22nd ICPC (2018) — Organizing Committee, Daffodil International University.

              <span style="font-size: 1.5em;">**Professional Development:**</span>
              * “Road to Research Duration” — Faculty research training, Dept. of CSE, Daffodil International University (26 Dec 2018).
              * “Machine Learning and AI” — Faculty workshop with SIGMOID, DIU (5–6 May 2018).
              * “How to Prepare a Good Research Proposal?” — Faculty workshop, DIU (17 Dec 2017).
              * “Participatory Engaging Techniques (PET)” — Teacher training, DIU (2017).

              <span style="font-size: 1.5em;">**Journal Reviewer**</span>
              * IEEE Transactions on Information Forensics and Security (TIFS) — <strong>Impact Factor: 6.3</strong>.
              * IEEE Transactions on Vehicular Technology (TVT) — <strong>Impact Factor: 6.1</strong>.
              * IEEE Transactions on Consumer Electronics (TCE) — <strong>Impact Factor: 4.3</strong>.
              * IEEE Transactions on Machine Learning in Communications and Networking Information (TMLCN).
              * Springer Nature Journal.

              <span style="font-size: 1.5em;">**Conference Reviewer**</span>
              * IEEE ICDCS 2024 — 44th International Conference on Distributed Computing Systems, Jersey City, NJ, USA.
              * MIDAS 2021 — International Conference on Machine Intelligence and Data Science Applications, Springer, Comilla University, Bangladesh.
              * IJCACI 2020 — International Joint Conference on Advances in Computational Intelligence, DIU, JU, SAU.

          url: ''
    design:
      columns: '2'

  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      default_button_index: 0
      buttons:
        - name: All
          tag: '*'
        - name: Privacy and Security
          tag: Privacy and Security
        - name: Federated Learning
          tag: Federated Learning
        - name: Large Language Model
          tag: Large Language Model   
        - name: Machine Learning
          tag: Machine Learning
    
    design:
      columns: '2'
      view: showcase
      flip_alt_rows: True

  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: citation

  - block: collection
    id: posts
    content:
      title: Recent Posts
      count: 5
      filters:
        folders:
          - post
        exclude_featured: true
      order: desc
    design:
      view: compact
      columns: '2'
  
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      email: mmia001@fiu.edu
      phone: +1 775 467 8870
      contact_links:
        - icon: facebook
          icon_pack: fab
          name: Md Jueal Mia
          link: ''
    design:
      columns: '2'
---
