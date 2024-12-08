# React Router Dom v6 Catch All Route '*' Issue

This repository demonstrates a problem with the catch-all route ('*') in React Router Dom v6.  The issue occurs when the catch-all route fails to match unexpected routes, instead showing the default route. The solution involves ensuring the catch-all route is placed last within the Routes component to correctly handle any unmatched paths.