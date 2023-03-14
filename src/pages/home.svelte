<Page name="home">
  <!-- Top Navbar -->
  <Navbar large sliding={false}>
    <NavLeft>
      <Link iconIos="f7:menu" iconAurora="f7:menu" iconMd="material:menu" panelOpen="left" />
    </NavLeft>
    <NavTitle sliding>vbqf</NavTitle>
    <NavRight>
      <Link iconIos="f7:menu" iconAurora="f7:menu" iconMd="material:menu" panelOpen="right" />
    </NavRight>
    <NavTitleLarge>vbqf</NavTitleLarge>
  </Navbar>
  <!-- Toolbar -->
  <Toolbar bottom>
    <Link>Left Link</Link>
    <Link>Right Link</Link>
  </Toolbar>
  <!-- Page content -->
  <Block strong>
    <p>This is an example of split view application layout, commonly used on tablets. The main approach of such kind of layout is that you can see different views at the same time.</p>

    <p>Each view may have different layout, different navbar type (dynamic, fixed or static) or without navbar.</p>

    <p>The fun thing is that you can easily control one view from another without any line of JavaScript just using "data-view" attribute on links.</p>
  </Block>

  <Block>
  <Row>
    <Col width="100" medium="50">
  <Card class="demo-card-header-pic">
    <CardHeader
      class="no-border"
      valign="bottom"
      style="background-image: url(https://cdn.framework7.io/placeholder/nature-1000x600-3.jpg)"
    >Journey To Mountains</CardHeader>
    <CardContent>
      <p class="date">Posted on January 21, 2015</p>
      <p>Quisque eget vestibulum nulla. Quisque quis dui quis ex ultricies efficitur vitae non felis. Phasellus quis nibh hendrerit...</p>
    </CardContent>
    <CardFooter>
      <Link><Icon f7="heart" /></Link>
      <Link>Read more</Link>
    </CardFooter>
  </Card>
  </Col><Col width="100" medium="50">
  <Card class="demo-card-header-pic">
    <CardHeader
      class="no-border"
      valign="bottom"
      style="background-image: url(https://cdn.framework7.io/placeholder/nature-1000x600-3.jpg)"
    >Journey To Mountains</CardHeader>
    <CardContent>
      <p class="date">Posted on January 21, 2015</p>
      <p>Quisque eget vestibulum nulla. Quisque quis dui quis ex ultricies efficitur vitae non felis. Phasellus quis nibh hendrerit...</p>
    </CardContent>
    <CardFooter>
      <Link><Icon f7="heart" /></Link>
      <Link>Read more</Link>
    </CardFooter>
  </Card>
</Col>
</Row>
</Block>

  <BlockTitle>Navigation</BlockTitle>
  <List>
    <ListItem link="/about/" title="About"/>
    <ListItem link="/form/" title="Form"/>
  </List>

  <BlockTitle>Modals</BlockTitle>
  <Block strong>
    <Row>
      <Col width="50">
        <Button fill raised popupOpen="#my-popup">Popup</Button>
      </Col>
      <Col width="50">
        <Button fill raised loginScreenOpen="#my-login-screen">Login Screen</Button>
      </Col>
    </Row>
  </Block>

  <BlockTitle>Panels</BlockTitle>
  <Block strong>
    <Row>
      <Col width="50">
        <Button fill raised panelOpen="left">Left Panel</Button>
      </Col>
      <Col width="50">
        <Button fill raised panelOpen="right">Right Panel</Button>
      </Col>
    </Row>
  </Block>

  <List>
    <ListItem
      title="Dynamic (Component) Route"
      link="/dynamic-route/blog/45/post/125/?foo=bar#about"
    />
    <ListItem
      title="Default Route (404)"
      link="/load-something-that-doesnt-exist/"
    />
    <ListItem
      title="Request Data & Load"
      link="/request-and-load/user/123456/"
    />
  </List>
</Page>
<script>
  import {
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
    Card,
    CardHeader,
    CardContent,
    CardFooter,
    Icon
  } from 'framework7-svelte';
</script>