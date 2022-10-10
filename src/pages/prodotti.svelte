<Page withSubnavbar>
  
    
    <Navbar title="Prodotti">
      <NavRight><Link back>Back</Link></NavRight>
      <Subnavbar inner={false}>
        <Searchbar
          searchContainer=".search-list"
          searchIn=".item-title"
          disableButton={!theme.aurora}
        />
      </Subnavbar>
    </Navbar>
    <List class="searchbar-not-found">
      <ListItem title="Nothing found"></ListItem>
    </List>
    <List class="search-list searchbar-found">
      <!--elemento-->
      <ListItem accordionItem title="Xiaomi Essential">
        <AccordionContent class="list">
          <!--colore-->
          <Card class="card">
            <Block class="mini_title">Modifiche</Block>
            <Block class="def">NO</Block>
            <Block class="mini_title">Velocità</Block>
            <Block class="def">20 kh/h</Block>
            <Block class="mini_title">Autonomia</Block>
            <Block class="def">20 km</Block>
            <Block class="mini_title">Prezzo</Block>
            <Block class="def">320 €</Block>
            <Block class="mini_title">Stato</Block>
            <Block class="def">Nuovo</Block>
          </Card>
          <Card class="card">
            <Block class="mini_title">Modifiche</Block>
            <Block class="def">SI</Block>
            <Block class="mini_title">Velocità</Block>
            <Block class="def">30 kh/h</Block>
            <Block class="mini_title">Autonomia</Block>
            <Block class="def">20 km</Block>
            <Block class="mini_title">Prezzo</Block>
            <Block class="def">420 €</Block>
            <Block class="mini_title">Stato</Block>
            <Block class="def">Nuovo</Block>
          </Card>
        </AccordionContent>
      </ListItem>
      <!--elemento-->
      <ListItem accordionItem title="Ducati Pro2">
        <AccordionContent class="list">
          <!--colore-->
          <Card class="card">
            <Block class="mini_title">Modifiche</Block>
            <Block class="def">NO</Block>
            <Block class="mini_title">Velocità</Block>
            <Block class="def">20 kh/h</Block>
            <Block class="mini_title">Autonomia</Block>
            <Block class="def">20 km</Block>
            <Block class="mini_title">Prezzo</Block>
            <Block class="def">320 €</Block>
            <Block class="mini_title">Stato</Block>
            <Block class="def">Nuovo</Block>
          </Card>
        </AccordionContent>
      </ListItem>
    </List>
</Page>
<script>
  import {
    Accordion, 
    AccordionItem, 
    AccordionContent,
    Card,
    Icon,
    Page,
    Navbar,
    NavLeft,
    NavTitle,
    NavTitleLarge,
    NavRight,
    Link,
    Toolbar,
    Block,
    BlockTitle,
    List,
    ListItem,
    Row,
    Col,
    Button, 
    theme, 
    Subnavbar, 
    Searchbar
  } from 'framework7-svelte';

  export let f7route, f7router; // just to remove debug message
</script>