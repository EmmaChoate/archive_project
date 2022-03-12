{% assign imagesample = site.data[site.metadata] | where_exp: 'item','item.format contains "image"' | first %}
{% capture imagesampleid %}{{imagesample.objectid | default: "https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b6_photographs_01.jpg"}}{% endcapture %}
{% assign pdfsample = site.data[site.metadata] | where_exp: 'item','item.format contains "pdf"' | first %}
{% capture pdfsampleid %}{{pdfsample.objectid | default: "https://digital.lib.uidaho.edu/utils/getfile/collection/ui_ep/id/21768/filename/uiext21768.pdf"}}{% endcapture %}
{% assign videosample = site.data[site.metadata] | where_exp: 'item','item.format contains "video"' | first %}
{% capture videosampleid %}{{videosample.objectid | default: "https://cdil.lib.uidaho.edu/storying-extinction/objects/trailcams/videos/ballcreek-cedarrub-birdonpath.mp4"}}{% endcapture %}
{% assign audiosample = site.data[site.metadata] | where_exp: 'item','item.format contains "audio"' | first %}
{% capture audiosampleid %}{{audiosample.objectid | default: "https://www.lib.uidaho.edu/digital/mp3s/Clouds.mp3"}}{% endcapture %}

## About The Book
Letters on the Elements of Botany is just as the title suggests, a comprised collection of letters written by Jean Jacques Rousseau on the elements of plants. The letters were originally published in French; Lettres Elementaires Sur La Botanique. 

Swiss Philosopher Jean-Jacques Rousseau (1712-1778)  took on many interests throughout his life. When he took up botany, it was because of a lady-of-interest. Though unknown, Rousseau’s lady is assumed to love flowers and the novel was supposed to reflect his knowledge on the topic. Many things can be said about these letters but one thing is for certain, they are delicately crafted for those who truly appreciate botany. Simply put, Letters is a beautiful collection of love letters. 

The letters remained unpublished until Thomas Martyn, professor of botany at the University of Cambridge, decided to use the text as study material thus translating Rousseau’s work to English. Martyn made some edits, added some letters of his own, and thus, changed the original message of the book. However, Martyn was very clear that it is informational but not to use it as a textbook. Martyn’s translation was published in 1785. 

