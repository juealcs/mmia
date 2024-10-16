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
      title: 'Achievements, Awards, and Services'
      date_format: Jan 2006
      items:
        - date_end: '2024-12-31'
          date_start: '2013-01-26'
          description: |2-
              <span style="font-size: 1.5em;">**Research Awards:**</span>
              * Received best paper award from the Third International Conference on Smart Systems: Innovations in Computing (SSIC), Springer, 2021.


              <span style="font-size: 1.5em;">**Scholarships:**</span>
              * Received university yearly scholarship for outstanding results.
              * Received scholarship for achieving the top position in the undergraduate entrance exam.
              
              <span style="font-size: 1.5em;">**Academic Contributions:**</span><br>
              <span style="font-size: 1.5em;">Committee Member</span>
              * <strong>IJCACI 2020</strong>: Served as a organizing committee member for International Joint Conference on Advances in Computational Intelligence, Daffodil International University, Bangladesh; Jahangirnagar University, Bangladesh and South Asian University, India

              
 
              <span style="font-size: 1.5em;">Journal Reviewer</span>
              * <strong>IEEE TIFS</strong>: Served as a reviewer for IEEE Transactions on Information Forensics & Security.    
              * <strong>IEEE TVT</strong>: Served as a reviewer for IEEE Transactions on Vehicular Technology.
              * <strong>IEEE TCE</strong>: Served as a reviewer for IEEE Transactions on Consumer Electronics.
              * <strong>Springer Nature</strong>: Served as a reviewer for the Springer Nature journal. 
    
              <span style="font-size: 1.5em;">Conference Reviewer</span>
              * <strong>ICDCS 2024</strong>: Served as a reviewer for the 44th IEEE International Conference on Distributed Computing Systems, Jersey City, New Jersey, USA.
              * <strong>MIDAS 2021</strong>: Served as a reviewer for the International Conference on Machine Intelligence and Data Science Applications (MIDAS 2021), Springer, Comilla University, Cumilla, Bangladesh.
              * <strong>IJCACI 2020</strong>: Served as a reviewer for International Joint Conference on Advances in Computational Intelligence, Daffodil International University, Bangladesh; Jahangirnagar University, Bangladesh and South Asian University, India    
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
        - name: Privacy and Security Issues in Federated Learning
          tag: Privacy and Security Issues in Federated Learning
        - name: Machine Learning
          tag: Machine Learning
        - name: Deep Learning
          tag: Deep Learning    
        - name: Computer Vision
          tag: Computer Vision
        - name: Intelligent Systems
          tag: Intelligent Systems
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
