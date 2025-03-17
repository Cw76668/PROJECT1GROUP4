# PROJECT1GROUP4

#GROUP MEMBERS: Kayla Valentine, Constance Wang, Kevin Choi, Jennifer Lee, Vivek Shah

# Our group is designing a database management platform for record labels to manage their businesses. This business will oversee artists’ albums, concerts, and other various income sources to better manage and quantify an artist’s revenue streams. Below are some critical business functions supported by our platform:
  #Artist and album management – The platform tracked signed and managed artists, tracks their albums, and handles music production.
  
  #Royalties – The business also oversees the income made from share of royalties.
  
  #Live event organization – The platform manages concerts, music festivals, and performances where artists showcase their work.
  
  #Managerial oversight – Managers oversee different aspects of the business, ensuring smooth operations.
# These are just a couple scenarios that our platform supports.

# About our data model:
#The data model represents a music industry database designed to store information about artists, their albums, songs, streaming data, concerts, ticket sales, collaborations, awards, record labels, contracts, and royalty payments. It captures key relationships between artists, their music, and business dealings. Each artist can release multiple albums and songs, and they may be associated with a record label through a contract. Albums belong to a single artist and contain multiple songs, while songs can feature multiple artists through collaborations. Collaborations exist as an associative entity between Artists and Songs. This is an oversimplification of reality, but it makes management easier by allowing artists to only be connected to their own songs either through an album or a collaboration (in reality an artist can release a single or an EP and songs do not necessarily belong to an album). Streaming data tracks digital music plays across platforms like Spotify and Apple Music, including stream counts and revenue. Concerts link artists to venues, with ticket sales recorded separately. The database also tracks royalties earned by artists, awards they have won, and details about record labels and contracts. Contracts exists as an associative entity between an Artist and their Record Label: an artist can sign multiple contracts (ie. nondisclosure, contracts for renewal, etc.), and a Record Label can have many contracts, yet each contract only belongs to one artist and one Record Label. This platform does not store information about individual music listeners, music licensing rights, physical sales, or reviews and ratings. It is well-suited for managing artist and music-related business operations, making it ideal for a music production company, record label, or streaming service focused on tracking artist performance and revenue.



