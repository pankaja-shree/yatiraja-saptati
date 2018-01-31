<template>
  <!-- Configure "view" prop for QLayout -->
  <q-layout>
    <q-toolbar slot="header">
      <!-- opens drawer below
      <button class="hide-on-drawer-visible" @click="$refs.drawer.open()">
        <i>menu</i>
      </button>
      -->
      <q-toolbar-title>
        Title
      </q-toolbar-title>
      <p>Sri Bhagavath Ramanuja is referred here as Yathiraja (the King of Saints). Some of his other names are Sri Bhashyakara, Udaiyavar, Emperumaanaar, Yathipathi and Lakshmanamuni. No amount of adulation can be too high for the great deeds of Sri Ramanuja, which included among others, founding and upholding our Sri Sampradaya in the form of Sri Visishtaadvaita philosophy, against all odds. It is he who showed us that the means and end for all souls is Sriman Narayana and established the route to salvation. One can never be able to fully pay back for this benevolence but can only make an attempt by singing the praise of the Acharya. Yathiraja Sapthathi comprises 74 verses, perhaps signifying the number of the Simhaasanaadhipathis Sri Ramanuja appointed to enable our Sampradaya thrive.
The hymn starts off with the first 10 slokas dedicated to the salutation of our Acharya Parampara, to which Sriman Narayana is the principal preceptor (Prathama Acharyan). The line-up in the descending order goes like this: The Lord, His Consort, Vishvaksena, Satakopa, Naathamunigal, UyyakKondaar, Manakkaal Nambi, Aala Vandhaar, Periya Nambi and Sri Ramanuja.
The 11th verse beautifully describes the form and virtues of Sri Ramanuja. Thereupon, it is all the glory of Sri Bhashyakara, expressively, exhaustively and exquisitely brought forth as only Swami Desika can.
Some of the most significant ones are given below with the sloka number in parentheses:
Sri Ramanuja being an incarnation of the Five Weapons of the Lord (12); of Vishvaksena (32); and Dhaththaathreya (63). He being the lustrous pivotal pendant in the line-up of our Sampradaya Acharyas (15). His feet being more important for salvation than even that of the Lord (20). The implication of his preaching-gesture (24 & 25). Sri Ramanuja being an amalgam of the three luminous bodies — the Fire, the Moon and the Sun (27). He being the saviour of the Supreme Being (Brahmam) from the devious designs of perverted schools of philosophy (38). The enormity and greatness of his works (47 to 54). The fate of the detractors of his distinguished works (55). The pure water from a well (SaalaikKinaru) offered to Lord Varadaraja by Sri Ramanuja, in turn, taking the form of showers of mercy pouring on us in all its abundance (62). The divine works of Sri Ramanuja investing in him (Sri Desika) all-conquering power (68). The greatness of the dust of the feet of Sri Ramanuja (64). Other philosophies taking a hurried hiding in front of Sri Ramanuja Sidhdhantha — Visishtaadvaita (70).
The author brings into play dual connotations aplenty in this virtuoso composition of his. Especially enchanting among them are: the ones involving Lord Krishna and Sri Ramanuja (13th sloka); Sri Ramanuja and a mountain (16); the great works of Sri Ramanuja and the Kalpa tree (31).
 In a categorical exposition of his contrasting attitude towards those who tread Sri Ramanuja's path and the others, Swami Desika declares thus in the 41st sloka: "I bear the lotus foot of the noble followers of Sri Ramanuja on my bowed head forever. By the same token, let it also be known that my left foot will be placed on the head of those with a raging madness in espousing the cause of other schools of philosophy." A classic metaphor marks the 72nd sloka, in which Sri Desika suggests that (it is enough) the roar of 'Kavi-Thaarkika Simham' — that is Yathiraja Sapthathi — be passed on to the ears of the rivals who entertain the thought of meeting us in a debate." Finally, as phala sruti, the author prays in sloka 73, "May the hymn bestow on the reader devotional intellect which encompasses both the worlds of the Lord — Leela Vibhuthi and Nithya Vibhuthi." And the concluding verse declares that those who learn the hymn will see the righteous path as clearly as a gooseberry in the palm and shall shine in the world so lustrously as to render the jealous rivals as ineffective as stars in the daytime.
</p>
    </q-toolbar>

    <!-- Navigation Tabs
    <q-tabs slot="navigation">
      <q-route-tab slot="title" icon="view_quilt" to="/layout/about" replace hide="icon" label="About" />
      <q-route-tab slot="title" icon="view_day" to="/layout/toolbar" replace hide="icon" label="Toolbar" />
      <q-route-tab slot="title" icon="view_day" to="/layout/tabs" replace label="Tabs" />
      <q-route-tab slot="title" icon="input" to="/layout/drawer" replace label="Drawer" />
    </q-tabs>
    -->

    <!-- Left Side Panel
    <div slot="left">
      <q-list no-border link inset-delimiter>
        <q-list-header>Essential Links</q-list-header>
        <q-item>
          <q-item-side icon="school" />
          <q-item-main label="Docs" sublabel="quasar-framework.org" />
        </q-item>
        <q-item>
          <q-item-side icon="record_voice_over" />
          <q-item-main label="Forum" sublabel="forum.quasar-framework.org" />
        </q-item>
        <q-item>
          <q-item-side icon="chat" />
          <q-item-main label="Gitter Channel" sublabel="Quasar Lobby" />
        </q-item>
        <q-item>
          <q-item-side icon="rss feed" />
          <q-item-main label="Twitter" sublabel="@quasarframework" />
        </q-item>
      </q-list>
    </div>
    -->

    <!-- Right Side Panel
    <div slot="right">
      ...
    </div>
    -->

    <router-view />

    <!-- Footer
    <q-toolbar slot="footer">
      ...
    </q-toolbar>
    -->
  </q-layout>
</template>

<script>
export default {
  data () {
    return {}
  }
}
</script>

<style>
</style>
