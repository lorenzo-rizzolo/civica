<Page name="home" id="home">
    <!-- Top Navbar -->
    <Navbar>
      <Block class="nav_title2">Sedi</Block>
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
      <ListItem accordionItem class="city_sedi" title="Torino">
        <AccordionContent class="list">
          <Card class="card">Corso Alessandro tassoni 19</Card>
        </AccordionContent>
      </ListItem>
      <!--elemento-->
      <ListItem accordionItem class="city_sedi" title="Piossasco">
        <AccordionContent class="list">
          <Card class="card">Via torino 31</Card>
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
      TreeviewItem, 
      Treeview,
      Subnavbar, 
      Searchbar, 
      Menu, 
      MenuItem 
    } from 'framework7-svelte';
  
  
    export let f7route, f7router; // just to remove debug message
  </script>