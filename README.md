# React-Routes

Ejemplo de uso 
```
  <Router>
      <div>
            <Switch>
                  <PublicRoute
                        exact
                        path="/login"
                        component={LoginScreen}
                        isAuthenticated={user.logged}
                  />
                  <PrivateRoute
                        path="/"
                        component={DashboardRoutes}
                        isAuthenticated={user.logged}
                  />
            </Switch>
      </div>
</Router>
```
