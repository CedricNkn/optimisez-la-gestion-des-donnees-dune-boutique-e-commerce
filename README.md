<p><img src="https://user.oc-static.com/upload/2023/05/10/16837285752827_OC-Bannieres-Projet_Student-Scenario_Bienvenue.png" alt="Bienvenue"></p>
<p>Aujourd’hui est un grand jour, vous commencez votre mission en tant que data analyst freelance chez BottleNeck, un marchand de vin très prestigieux. Votre manager sur cette mission (Laurent) vous accueille chaleureusement et vous propose de partager un petit café avec le reste de l’équipe du service Numérique. L’ambiance est bonne, et vous voilà déjà parfaitement intégré dans cette équipe détendue mais professionnelle.</p>
<figure><a href="https://user.oc-static.com/upload/2020/11/23/16061348800222_Capture%20d%E2%80%99e%CC%81cran%202020-11-23%20a%CC%80%2013.33.23.png" class="oc-imageLink oc-imageLink--disabled"><img src="https://user.oc-static.com/upload/2020/11/23/16061348800222_Capture%20d%E2%80%99e%CC%81cran%202020-11-23%20a%CC%80%2013.33.23.png" alt="Logo de Bottleneck"></a>
<figcaption>Logo de Bottleneck</figcaption>
</figure>
<p>Après les premières présentations, effectuées dans une ambiance des plus conviviales, Laurent vous explique les enjeux de votre première mission :</p>
<blockquote>
<p><em>“</em>Actuellement, pour gérer nos ressources, nos clients, etc., on utilise un ERP qui n’est absolument pas relié à notre site de vente en ligne. Pour être tout à fait honnête, les outils en place sont vraiment artisanaux et dans ces conditions, la gestion des stocks est vraiment complexe et notre visibilité en termes d’analyse des ventes sur le Net est vraiment réduite, car très peu de personnes ont accès au back-office. En attendant une solution plus centralisée, un rapprochement entre les 2 bases, même manuel, pourrait être très utile…</p>
<p>Ta première mission se passe en 3 points.</p>
<p>Premièrement, j’ai besoin que tu rapproches deux exports : un export de l’ERP contenant les références produit, leur prix de vente et leur état de stock, et un export d’une table de l’outil de CMS contenant les informations des produits commercialisés en ligne (nom, description, nombre de ventes...).</p>
<p>L’export issu de la boutique en ligne contient le nombre de ventes pour chaque produit depuis sa mise en ligne, il ne permet pas d’analyser l'évolution des ventes dans le temps.</p>
<p>Je vais t’envoyer un mail dès la fin de notre entretien avec ces 2 exports en pièce jointe.</p>
<p>En plus de ces 2 exports, tu vas bénéficier d’une aide précieuse car Sylvie, notre ancienne stagiaire, a réalisé un travail de fourmi. Elle a créé un tableau Excel qui permet d’établir le lien entre la référence du produit dans l’ERP (product_id) et la référence du même produit dans la base de la boutique en ligne (SKU).</p>
<p>Deuxièmement, une fois le rapprochement effectué, je souhaiterais avoir le chiffre d’affaires par produit, ainsi que le total du chiffre d’affaires réalisé en ligne.</p>
<p>Troisièmement et pour finir, je me demande s’il n’y a pas eu des erreurs de saisie dans certains prix des produits. J'aimerais que tu effectues une analyse sur cette variable afin de détecter d’éventuelles valeurs aberrantes, de les lister et d’en faire une représentation graphique pour plus de lisibilité.</p>
<p>Nous voudrions présenter tes résultats lors de la prochaine réunion de COPIL. Cela permettrait de montrer nos progrès. je te conseille de nous faire une présentation, mais tu peux également faire un notebook que tu présenteras à l’assemblée pour expliquer ta démarche et les incohérences (je pense que tu peux en trouver facilement au moins 5).</p>
<p>Tu peux utiliser R ou Python comme tu préfères, nous n'avons pas de préférence de notre côté.”</p>
</blockquote>
<p>&nbsp;</p>
<p>Après vous avoir méticuleusement délivré ces consignes, Laurent vous accompagne à votre poste de travail.</p>
<p>Juste avant de vous laisser prendre votre mission à bras-le-corps, il vous réitère qu’il va vous faire suivre les exports par mail, ainsi que la table de liaison de Sylvie.&nbsp;</p>
<p><img src="https://user.oc-static.com/upload/2023/05/10/168372864084_OC-Bannieres-Projet_Temps_Quelques-minutes-plus-tard.png" alt="Quelques minutes plus tard"></p>
<p>&nbsp;&nbsp;Vous recevez le mail des exports de tables :&nbsp;</p>
<div class="oc-tableContainer"><table>
<tbody>
<tr>
<td>
<p><strong>Objet </strong>: Exports tables<br><strong>De </strong>: Laurent<br><strong>À </strong>: Moi</p>
</td>
</tr>
<tr>
<td>
<p>Re,</p>
<p>Voici les 2 exports dont nous avons parlé ce matin. Tu as le fichier issu de l’ERP (erp.xlsx) et le fichier de la table produit de notre plateforme de vente en ligne (web.xlsx). Je te laisse prendre connaissance de ces éléments.</p>
<p>Je ne vais pas t’apprendre ton métier mais n’oublie pas les bonnes pratiques :&nbsp;</p>
<ul>
<li>Pas de problème d’encodage</li>
<li>Tester l’unicité des clés,</li>
<li>Vérifier les jointures (type de jointure, nombre de produits jointés, etc.)</li>
<li>Suppression ou modification des lignes justifiées</li>
</ul>
<p>&nbsp;</p>
<p>N’hésite pas à me solliciter si tu as des questions.</p>
<p>Cordialement,<br><strong>Laurent</strong></p>
</td>
</tr>
<tr>
<td>
<p><strong>Pièces jointes</strong> :&nbsp;</p>
<ul>
<li><a class="custom-link" href="https://s3.eu-west-1.amazonaws.com/course.oc-static.com/projects/DAN_V2_P5/Fichier_erp.xlsx">erp.xls</a></li>
<li><a class="custom-link" href="https://s3.eu-west-1.amazonaws.com/course.oc-static.com/projects/DAN_V2_P5/Fichier_web.xlsx">web.xlsx</a></li>
</ul>
</td>
</tr>
</tbody>
</table></div>
<p>&nbsp;<img src="https://user.oc-static.com/upload/2023/05/10/16837287492528_OC-Bannieres-Projet_Temps_Quelques-secondes-plus-tard.png" alt="Quelques secondes plus tard"></p>
<p>Le mail du tableau de liaisons arrive :</p>
<div class="oc-tableContainer"><table>
<tbody>
<tr>
<td>
<p><strong>Objet</strong> : Fwd: Table de liaison</p>
<p><strong>De </strong>: Laurent<br><strong>À </strong>: Moi</p>
</td>
</tr>
<tr>
<td>
<p>---------- Forwarded message ---------</p>
<p><strong>Objet</strong>: Table de liaison<br><strong>De</strong> : Sylvie<br><strong>À</strong> : Laurent</p>
<p>Bonjour Laurent,</p>
<p>Comme promis, voici en pièce jointe le fichier Excel qui liste les product_id de l’ERP avec leur référence côté Web. La liste des product_id est exhaustive, mais pour les références côté Web, j’en suis moins sûre... J’ai peiné à rapprocher certaines références.</p>
<p>Je suis désolée, mais je me rends compte à l’instant que j’ai également mal nommé la colonne dans le fichier Excel. En fait, la colonne id_web dans mon fichier correspond au SKU des produits dans la boutique en ligne.</p>
<p>Je profite également de ce mail pour te remercier de m’avoir permis de faire mon stage avec toi. C’était une expérience formidable, et j’ai vraiment apprécié ton aide bienveillante.</p>
<p>Merci.<br>À très bientôt.</p>
<p>Cordialement,<br><strong>Sylvie</strong></p>
</td>
</tr>
<tr>
<td>
<p><strong>Pièce jointe</strong> : <a class="custom-link" href="https://s3.eu-west-1.amazonaws.com/course.oc-static.com/projects/DAN_V2_P5/fichier_liaison.xlsx">liaison.xlsx</a></p>
</td>
</tr>
</tbody>
</table></div>
<p>&nbsp;</p>
<div class="oc-tableContainer"><table>
</table></div>
<p>&nbsp;</p>
<aside data-claire-semantic="information">
<p>Dans ce projet, vous êtes libre d’utiliser le langage de programmation de votre choix entre <strong>R et Python</strong> pour mener à bien votre analyse. Vous pouvez utiliser choix Jupyter (pour R et pour Python) ou R Markdown (pour R).</p>
</aside>
<p><img src="https://user.oc-static.com/upload/2023/05/10/1683728862027_OC-Bannieres-Projet_Student-Scenario_Livrables.png" alt="Livrables"></p>
<aside data-claire-semantic="information">
<p>Avant d'envoyer vos livrables, n'hésitez pas à consulter cette <a class="custom-link" href="https://s3.eu-west-1.amazonaws.com/course.oc-static.com/projects/DAN_V2_P5/Check+list+auto+evalution+P5+(1).pdf">check list d'auto-évaluation</a>.</p>
</aside>
<ol>
<li>Le notebook R Markdown ou Jupyter.</li>
</ol>
