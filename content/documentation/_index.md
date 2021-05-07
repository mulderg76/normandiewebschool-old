---
title: La documentation sur l'école
date: 2019-05-12T06:14:34.000+00:00
description: Renseignez vos coordonnées et accédez à toute la documentation sur l'école.
banner:
  title: Accédez à la <span class="font-weight-medium">documentation</span>
  title-line-twho: ''
  subtitle: 'Remplissez les champs ci-dessous pour avoir accès à notre plaquette et
    les fiches programmes de l''école. '
  image: "/uploads/banner_documentation.jpg"
documents:
  enable: true
  title: Téléchargez les documents
  subtitle: <p>Téléchargez les documents de présentation des différentes filières
    à la <strong>Normandie Web School</strong>. </p><p>N'hésitez pas à demander un
    entretien pédagogique en <a href="https://normandiewebschool.fr/inscription/">cliquant
    ici</a> après votre lecture.</p>
  document:
  - icon: "/uploads/icn-cloud.png"
    name: Présentation générale de la NWS
    format: PDF
    document: "/uploads/plaquette-nws-generale.pdf"
  - icon: "/uploads/icn-cloud.png"
    name: Année préparatoire
    format: PDF
    document: "/uploads/1ere-annee-cursus-initial.pdf"
  - icon: "/uploads/icn-cloud.png"
    name: Filière Web Design & Communication visuelle
    format: PDF
    document: "/uploads/design-graphique.pdf"
  - icon: "/uploads/icn-cloud.png"
    name: Filière Web Développement
    format: PDF
    document: "/uploads/developpement.pdf"
  - icon: "/uploads/icn-cloud.png"
    name: Filière Web Marketing
    format: PDF
    document: "/uploads/marketing.pdf"
  - icon: "/uploads/icn-cloud.png"
    name: Filière Community Management
    format: PDF
    document: "/uploads/community-management.pdf"
  - icon: "/uploads/icn-cloud.png"
    name: Mastère "Expert digital"
    format: PDF
    document: "/uploads/mastere.pdf"
form:
  title: Vos coordonnées
  subtitle: ''
  enable: true
  input:
  - icon: "/uploads/icn-user.png"
    placeholder: Votre nom de famille*
    type: last_name
    required: true
    name: nom
    width: "50"
  - icon: "/uploads/icn-user.png"
    placeholder: Votre prénom*
    type: text
    required: true
    name: first_name
    width: "50"
  - icon: "/uploads/icn-mail.png"
    placeholder: Votre adresse e-mail*
    type: email
    required: true
    name: email
    width: "50"
    padding: pr-lg-1
  - icon: "/uploads/icn-mail.png"
    placeholder: Confirmer votre adresse e-mail*
    type: email
    required: true
    name: email_confirmation
    width: "50"
    padding: pl-lg-1
  - icon: "/uploads/icn-phone.png"
    placeholder: Votre numéro de téléphone
    type: phone
    required: false
    name: phone
    width: "50"
  - icon: "/uploads/icn-msg.png"
    placeholder: Votre niveau d'étude
    type: text
    required: false
    name: niveau
    width: "50"
  - icon: "/uploads/icn-msg.png"
    placeholder: Votre intérêt (filière et année)
    type: choix
    required: false
    name: choix
    width: "100"
  checkbox:
  - content: En soumettant ce formulaire, j'accepte que les informations saisies soient
      exploitées dans le cadre d'apport d'information concernant les formations proposées
      par l'école.
    required: true
    name: RGPD
  - content: J'accepte de recevoir les actualités de la Normandie Web School  ainsi
      que des publications à portée commerciale.
    required: false
    name: newsletter
seo_image: ''
menu:
  top:
    name: Documentation
    URL: documentation
    weight: 3
  main:
    name: Documentation
    weight: 9

---
