## Description
Federated Learning (FL) offers the benefits of machine learning without compromising the privacy of the users. However, the implementation of federated learning introduces new challenges for optimizing the accuracy of ML models as well as converging to the optimal points due to the nature and distribution of training data used in federated learning. Namely, there are three attributes of data in federated learning that badly impede the optimization process: Massively Distributed Data, Non IID Data and Unbalanced Data[2]. Nevertheless, progress has been made to improve federated learning by exploring different adaptive server aggregation algorithms[1]. One finding from this study showed that model accuracy improvement was more sensitive to tuning the client update schemes than tuning the accuracy of the server aggregation method. As such, our CSC 2228 course project will use this finding as inspiration to explore how to improve the model accuracy of unbalanced Non IID data by implementing different client update schemes. While different client update schemes have been implemented and tested in “Optimization in Federated Learning'' to explore which provides the greatest accuracy gains, this work focused solely on Non IID data. Unbalanced Non IID data presents significant challenges for realizing competitive model accuracy above and beyond the challenges presented by Non IID data alone. To our knowledge, our project will be the first to explore whether federated learning model accuracy of unbalanced Non IID data can be improved through implementing different client update schemes.

## Team member
Rachel Phinnemore, Yufei Kang, Tianyu Wang

## Timeline
<table>
  <thead>
    <tr>
      <th style="text-align: center", width=250px>Date</th>
      <th style="text-align: center">Milestone</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Week 1: Feb 2nd - Feb 9th </td>
      <td>Finding existing code to use to allow us to focus on implementing new client update schemes <br/><br/>
        Setting up environment and ensuring existing code for us to build upon works </td>
    </tr>
    <tr>
      <td>Week 2: Feb 9th - Feb 16th </td>
      <td>Create Non-IID dataset and unbalanced Non-IID data </td>
    </tr>
    <tr>
      <td>Week 2-3: Feb 9th - Feb 23th</td>
      <td>Research different client update schemes to implement and implement them </td>
    </tr>
    <tr>
      <td> Week 3: Feb 16th - Feb 23rd </td>
      <td> Implement method to measure accuracy of model on client and global model <br/><br/>
        Start writing progress report</td>
    </tr>
    <tr>
      <td> Week 4: Feb 23rd - Mar 2nd  </td>
      <td> 
        Running experiments to tune hyper parameters of client update schemes <br/><br/>
        Begin outline for paper 
      </td>
    </tr>
    <tr>
      <td> Week 5-7: Mar 2nd - Mar 16th </td>
      <td> 
        Experiment running <br/><br/>
        Get feedback from TA on paper outline <br/><br/>
        Writing Paper 
      </td>
    </tr>
    <tr>
      <td> Week 7-8: Mar 17th - Mar 31th </td>
      <td> 
        Prepare presentation <br/><br/>
        Get feedback from TA on presentation outline <br/><br/>
        Polish paper
      </td>
    </tr>
    <tr>
      <td> Week 9: Apr 1st - Apr 7th </td>
      <td> 
        Polish presentation <br/><br/>
        Do practice presentation dry run 
      </td>
    </tr>
    <tr>
      <td> Week 10: Apr 7th - April 16th </td>
      <td>
        Submit final report
      </td>
    </tr>
  </tbody>
</table>
